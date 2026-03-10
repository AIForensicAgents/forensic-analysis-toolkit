# Image Forensics Examples

## AI-Generated Image Detection

```javascript
// Analyze an image for AI generation probability
const result = await analyzeImageSpectral(
  "https://drive.google.com/file/d/YOUR_FILE_ID/view"
);

console.log("AI Probability:", result.aiDetection.probability);
console.log("Confidence:", result.aiDetection.confidence);
console.log("Active Signals:", Object.entries(result.aiDetection.signals)
  .filter(([k, v]) => v > 0.3)
  .map(([k, v]) => k + ": " + v));
```

## Signals Analyzed
- Benford's Law deviation
- GLCM texture homogeneity
- Gradient magnitude distribution
- Local Binary Pattern diversity
- JPEG compression artifacts
- Inter-channel correlation
- Pixel periodicity
- Color uniformity
- Noise characteristics
- Frequency domain analysis
- Edge density patterns
- Entropy analysis
- Saturation patterns
