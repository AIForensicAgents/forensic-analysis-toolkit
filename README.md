<!-- A comprehensive forensic topics and methods reference for digital forensics, AI forensics, and data analysis — covering image forensics, document forensics, OSINT, AI detection, behavioral analysis, automated reporting, and cross-platform investigations. -->

<div align="center">

# 🔬 ForensicAI Toolkit

### A Comprehensive Digital Forensics & AI Investigation Framework

![Forensics](https://img.shields.io/badge/Digital_Forensics-Expert-critical?style=for-the-badge&logo=microscope)
![AI Detection](https://img.shields.io/badge/AI_Detection-13_Signals-blue?style=for-the-badge&logo=openai)
![OSINT](https://img.shields.io/badge/OSINT-Multi--Platform-green?style=for-the-badge&logo=google)
![Status](https://img.shields.io/badge/Status-Active_Development-yellow?style=for-the-badge&logo=statuspal)
![Methods](https://img.shields.io/badge/Methods-75+-purple?style=for-the-badge&logo=bookstack)
![License](https://img.shields.io/badge/License-Research_Only-lightgrey?style=for-the-badge&logo=creativecommons)

---

*Bridging traditional digital forensics with next-generation AI analysis capabilities.*
*From pixel-level image authentication to cross-platform behavioral profiling.*

[Image Forensics](#-image-forensics) •
[Document Forensics](#-document-forensics) •
[Communication Forensics](#-communication-forensics) •
[Data Intelligence & OSINT](#-data-intelligence--osint) •
[AI Detection & Authentication](#-ai-detection--authentication) •
[Behavioral Analysis](#-behavioral-analysis) •
[Automated Reporting](#-automated-reporting) •
[Cross-Platform Investigation](#-cross-platform-investigation)

</div>

---

## 📖 Table of Contents

- [Overview](#overview)
- [🖼️ Image Forensics](#-image-forensics)
- [📄 Document Forensics](#-document-forensics)
- [💬 Communication Forensics](#-communication-forensics)
- [🌐 Data Intelligence & OSINT](#-data-intelligence--osint)
- [🤖 AI Detection & Authentication](#-ai-detection--authentication)
- [🧠 Behavioral Analysis](#-behavioral-analysis)
- [📊 Automated Reporting](#-automated-reporting)
- [🔗 Cross-Platform Investigation](#-cross-platform-investigation)
- [Methodology Matrix](#-methodology-matrix)
- [Getting Started](#-getting-started)

---

## Overview

This repository catalogs **75+ forensic investigation methods** that can be implemented using a unified AI-powered system with capabilities spanning image analysis, document processing, multi-platform communication analysis, web intelligence gathering, and automated reporting. Each method is designed to be reproducible, auditable, and suitable for both research and applied investigation contexts.

> **⚠️ Ethical Notice:** These methods are intended for authorized forensic investigation, academic research, and security auditing only. Always ensure proper legal authorization before conducting any investigation.

---

## 🖼️ Image Forensics

*Techniques for authenticating, analyzing, and investigating digital images at the pixel, statistical, and semantic level.*

| # | Topic | Description | Capabilities Used | Difficulty |
|:-:|-------|-------------|-------------------|:----------:|
| 1 | **🔢 Benford's Law Anomaly Mapper** | Applies first-digit frequency analysis to DCT coefficients across image blocks to reveal localized tampering — regions where pixel statistics deviate from the natural logarithmic distribution expected in authentic photographs. | Image spectral analysis, AI prompt execution, Google Sheets, PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 2 | **🧱 GLCM Texture Inconsistency Scanner** | Computes Gray-Level Co-occurrence Matrices across sliding windows to detect texture discontinuities that indicate splicing, cloning, or AI-inpainted regions that break the natural spatial texture coherence. | Image spectral analysis (GLCM texture signal), Image editing, Google Docs reporting | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 3 | **🌀 LBP Forgery Heatmap Generator** | Generates Local Binary Pattern histograms per image region and visualizes deviations as forensic heatmaps, highlighting areas where micro-texture patterns are inconsistent with the surrounding content. | Image spectral analysis (LBP signal), Image generation (heatmap overlays), PDF generation | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 4 | **📐 Gradient Distribution Profiler** | Analyzes the statistical distribution of image gradients (edge strength and direction) to detect unnatural uniformity or abrupt transitions that suggest compositing or AI generation. | Image spectral analysis (gradient distribution), AI prompt execution, Google Sheets | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 5 | **🔄 Periodic Artifact Detector** | Performs frequency-domain analysis to identify repeating patterns and periodic artifacts — telltale signatures of GAN-generated images, resampling, or copy-move forgery. | Image spectral analysis (periodicity signal), AI prompt execution, PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 6 | **🎨 Channel Correlation Forensics** | Examines statistical correlations between RGB (and potentially YCbCr) channels to detect manipulations — authentic images exhibit predictable inter-channel relationships that splicing and AI generation disrupt. | Image spectral analysis (channel correlation), Google Sheets, Google Docs | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 7 | **📦 JPEG Ghost Analysis** | Detects double-compression artifacts by analyzing quantization table residuals, revealing regions that were saved at a different quality level — a classic indicator of image manipulation. | Image spectral analysis (compression artifacts), Image editing, PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 8 | **🔍 Full-Spectrum 13-Signal Authentication** | Executes the complete 13-signal spectral analysis pipeline in a single pass, generating a comprehensive authenticity confidence score with signal-by-signal breakdown and visual evidence. | Image spectral analysis (all 13 signals), AI prompt execution, Google Docs, Google Slides, PDF generation | ![Expert](https://img.shields.io/badge/-Expert-red) |
| 9 | **🖼️ Reverse Image Provenance Tracker** | Scrapes the web for visually similar images, traces the publication timeline, and identifies the earliest known instance to establish image provenance and detect unauthorized modifications. | Web scraping, Image spectral analysis, AI prompt execution, Google Sheets, Google Docs | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 10 | **🏭 AI Image Generation Lineage Detector** | Determines which specific AI model family (DALL-E, Midjourney, Stable Diffusion, Gemini) likely generated an image by analyzing model-specific spectral fingerprints and artifact patterns. | Image spectral analysis, AI prompt execution (multi-model comparison), Google Sheets, PDF generation | ![Expert](https://img.shields.io/badge/-Expert-red) |
| 11 | **📸 Metadata Stripping & Recovery Audit** | Examines EXIF, IPTC, and XMP metadata fields for inconsistencies, detects evidence of metadata stripping, and attempts to recover forensically valuable embedded information. | Image spectral analysis, AI prompt execution, Google Docs, Google Sheets | ![Beginner](https://img.shields.io/badge/-Beginner-brightgreen) |
| 12 | **🌓 Shadow & Lighting Consistency Analyzer** | Uses AI vision models to analyze shadow directions, lighting angles, and specular highlights across objects in a scene to detect compositing where light sources are physically inconsistent. | AI prompt execution (vision models), Image spectral analysis, Image editing (annotation), PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |

---

## 📄 Document Forensics

*Methods for investigating the authenticity, origin, and integrity of digital documents.*

| # | Topic | Description | Capabilities Used | Difficulty |
|:-:|-------|-------------|-------------------|:----------:|
| 13 | **📝 Authorship Attribution Engine** | Analyzes writing style, vocabulary richness, sentence structure patterns, and stylometric fingerprints across documents to determine likely authorship or detect ghostwriting. | AI prompt execution (multi-model consensus), Google Docs, Google Sheets, Web scraping | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 14 | **🔀 Document Version Diff Forensics** | Compares multiple versions of a document (from Google Drive or GitHub) to identify suspicious modifications, backdated edits, or selectively altered passages with timestamped audit trails. | Google Drive, GitHub management, AI prompt execution, Google Docs (inline comments), Google Sheets | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 15 | **✍️ AI-Written Content Fingerprinting** | Detects AI-generated text within documents using multi-model cross-examination — each AI model analyzes the text and a meta-analysis identifies statistical patterns characteristic of machine authorship. | AI prompt execution (GPT-5, Claude Opus 4, Gemini — all three), Google Docs, PDF generation | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 16 | **📊 Statistical Plagiarism Mapper** | Scrapes web sources, compares n-gram distributions, and generates similarity matrices to visualize the degree and location of textual overlap between a suspect document and known sources. | Web scraping, AI prompt execution, Google Sheets, Google Slides, PDF generation | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 17 | **🔐 Document Integrity Chain-of-Custody Logger** | Creates a tamper-evident chain-of-custody record for digital evidence files by logging hashes, timestamps, access events, and storage locations across Google Drive with automated notifications. | Google Drive, Secret management, Email (Gmail API), Google Sheets, Calendar management | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 18 | **📋 Form & Contract Anomaly Detector** | Analyzes PDFs and documents for inconsistencies in fonts, formatting patterns, date logic errors, and semantic contradictions that may indicate fraudulent modification of legal or financial documents. | AI prompt execution, PDF generation, Google Docs (inline comments), Web scraping | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 19 | **🏛️ Legal Citation Verification Engine** | Extracts legal citations from documents, cross-references them against web sources and known databases, and flags fabricated or hallucinated case references — critical in the age of AI-generated legal filings. | AI prompt execution, Web scraping, Wikipedia summarization, Google Docs (inline comments), Google Sheets | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 20 | **📚 Source Code Provenance Analyzer** | Examines code repositories for licensing violations, identifies code lineage through commit history analysis, and detects AI-generated code blocks through stylistic analysis. | GitHub management, AI prompt execution, Google Docs (code refactoring), Google Sheets | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 21 | **🏗️ Building Code Compliance Auditor** | Cross-references construction documents and permits against Palo Alto building code databases to identify discrepancies, expired permits, or non-compliant modifications in property investigations. | Palo Alto building codes search, AI prompt execution, PDF generation, Google Docs, Google Sheets | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 22 | **📖 Historical Text Authentication** | Leverages Project Gutenberg's corpus to verify whether passages attributed to historical figures are authentic, misattributed, or fabricated — using both source matching and stylometric analysis. | Project Gutenberg search, AI prompt execution, Wikipedia summarization, Google Docs, PDF generation | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |

---

## 💬 Communication Forensics

*Investigating patterns, authenticity, and hidden information within digital communications.*

| # | Topic | Description | Capabilities Used | Difficulty |
|:-:|-------|-------------|-------------------|:----------:|
| 23 | **📧 Email Header & Routing Forensics** | Parses email headers to trace the actual routing path, identifies spoofed sender addresses, analyzes SPF/DKIM/DMARC compliance, and detects phishing infrastructure through domain analysis. | Email (Gmail API), AI prompt execution, Web scraping, Google Sheets, PDF generation | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 24 | **🎭 Impersonation Detection Suite** | Compares writing style, timing patterns, and linguistic fingerprints of communications against a known baseline to detect account takeover or impersonation in email and Slack channels. | Email (Gmail API), Slack messaging, AI prompt execution (multi-model), Google Sheets, Google Docs | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 25 | **🕸️ Communication Network Mapper** | Builds graph visualizations of email and Slack communication networks, identifies key nodes, unusual connection patterns, and communication anomalies that may indicate collusion or information leaks. | Email list management, Slack messaging, AI prompt execution, Google Sheets, Web app generation | ![Expert](https://img.shields.io/badge/-Expert-red) |
| 26 | **⏰ Temporal Communication Pattern Analyzer** | Maps email and message timestamps to detect anomalous activity patterns — messages sent at unusual hours, burst communications before key events, or automated bot-like timing regularity. | Email (Gmail API), Slack messaging, AI prompt execution, Google Sheets, Google Slides | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 27 | **🔗 Phishing Campaign Deconstructor** | Dissects suspected phishing emails by analyzing embedded URLs, QR codes, attachment metadata, domain age, and social engineering language patterns to profile threat actors and campaign infrastructure. | Email (Gmail API), Web scraping, QR code generation (for comparison), AI prompt execution, Google Sheets, PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 28 | **💬 Sentiment Drift Detector** | Tracks emotional tone and sentiment trajectories across communication threads over time to identify inflection points — useful in harassment investigations, radicalization analysis, or insider threat detection. | AI prompt execution, Email (Gmail API), Slack messaging, Google Sheets, Google Slides | ![Intermediate](https://img.shields.io/badge/-Intermediate-yellow) |
| 29 | **🤖 Bot vs. Human Communication Classifier** | Analyzes message patterns, response latency, vocabulary diversity, and typing dynamics metadata to classify whether communications originated from a human, a chatbot, or an AI assistant. | AI prompt execution (multi-model consensus), Slack messaging, Email (Gmail API), Google Sheets, PDF generation | ![Advanced](https://img.shields.io/badge/-Advanced-orange) |
| 30 | **📎 Attachment Forensics Pipeline** | Automatically extracts, catalogs, and analyzes all attachments from email and Slack communications — running image forensics on photos, document analysis on files, and flagging suspicious payloads. | Email (Gmail API), Slack messaging, Image spectral analysis, AI prompt execution, Google Drive, Google Sheets | ![Expert](https://img.shields.io/badge/-Expert-red) |

---

## 🌐 Data Intelligence & OSINT

*Open-source intelligence gathering, data correlation, and investigative research methods.*

| # | Topic | Description | Capabilities Used | Difficulty |
|:-:|-------|-------------|-------------------|:----------:|
| 31 | **🔎 Entity Deep-Dive Dossier Generator** | Aggregates information about a person, company, or organization from multiple open sources (web, Wikipedia, BBB, news) into a comprehensive, cross-referenced intelligence dossier with confidence ratings. | Web scr