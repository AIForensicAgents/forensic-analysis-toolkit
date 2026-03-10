# Document Forensics Examples

## Automated Document Review

```javascript
// Review a Google Doc with AI-powered inline comments
const review = await reviewGoogleDoc({
  docUrl: 'https://docs.google.com/document/d/DOC_ID/edit'
});

console.log("Summary:", review.summary);
console.log("Comments Added:", review.commentsAdded);
```

## Content Extraction & Analysis

```javascript
// Extract and summarize content from multiple URLs
const analysis = await extractAndSummarizeUrls({
  urls: ['https://example.com/page1', 'https://example.com/page2'],
  topic: 'forensic evidence analysis'
});
```
