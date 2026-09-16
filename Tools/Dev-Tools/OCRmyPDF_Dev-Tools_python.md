---
source: https://github.com/ocrmypdf/OCRmyPDF
aliases:
  - OCRmyPDF
  - ocrmypdf/OCRmyPDF
tags: [python, python, pdf, ocr, tesseract, cli, image-processing, shell, dockerfile, url]
category: Dev-Tools
stars: 34162
org: ocrmypdf
primary_language: Python
languages: [Python, Shell, Dockerfile, url]
credibility_score: 72.0/100
date_processed: 2026-07-13
last_release: 2026-04-06
cover: attachments/banners/OCRmyPDF_banner.png

---

![banner](attachments/banners/OCRmyPDF_banner.png)

# OCRmyPDF

> **TL;DR:** Adds OCR text layer to scanned PDFs, making them searchable and copy-pasteable.

**`ocrmypdf/OCRmyPDF`** · ⭐ 34,162 · 🔧 Python

## What is it?
OCRmyPDF is a command-line Python tool that adds an OCR text layer to scanned or image-based PDF files, enabling them to be searched, indexed, and have their text content copied/pasted. It processes PDFs by extracting images from each page, running Tesseract OCR on those images with support for multiple languages (e.g., English, French), and then merging the resulting searchable text layers back into a new PDF file.

## How does it work?
The tool uses Python as its primary language and leverages Tesseract OCR (typically via pytesseract) to perform optical character recognition on image data extracted from PDF pages. It relies on PDF manipulation libraries such as PyPDF2 or pdfplumber to split the original PDF into individual pages, convert page images to a format Tesseract can process, run OCR with language-specific options, and then combine the text layer with the original visual content into a new PDF/A-compliant file. The CLI interface allows users to specify languages (e.g., '-l eng+fra'), rotate pages that are misaligned, deskew crooked documents, set metadata like titles, and configure parallel processing via --jobs.

## Why is it important? (Core Value)
For the user's objectives, OCRmyPDF provides a self-hosted, open-source alternative to SaaS PDF processing services—crucial for preserving document confidentiality when working with sensitive or proprietary materials. It directly supports the user's interest in developer productivity tools by offering a scriptable CLI that can be integrated into automation pipelines (e.g., batch-processing scanned archives). The tool's ability to handle multi-language OCR, deskewing, and PDF/A output aligns well with infrastructure and documentation workflows the user curates, making it a credible, adoptable utility for their knowledge base.

## Key Features & Technologies
- Command-line interface (CLI) with Python
- Tesseract OCR engine integration
- Multi-language text layer support (e.g., eng+fra)
- PDF/A output format compliance
- Page rotation and deskewing capabilities
- Metadata editing (title, author, etc.)
- Parallel processing with --jobs flag

## Difference from Others
Compared to alternatives like Adobe Acrobat Pro (commercial), pdftotext (text extraction only), or online OCR services (privacy concerns), OCRmyPDF stands out as an open-source CLI tool that both adds searchable text AND preserves the original PDF layout. Unlike PyPDF2 or pdfplumber alone, it specifically targets scanned/image-based PDFs with OCR capabilities. It also supports PDF/A archival format by default, which many other tools don't emphasize.

## 🏢 Organization & Credibility
- **Developer:** ocrmypdf
- **Reputation:** Unknown
- **Stars:** 34,162
- **Forks:** 2360
- **Recent Activity:** 86 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** Python, Shell, Dockerfile, url
- **Last Release:** 2026-04-06
- **Quality:** ✅ good

## 💡 My Ideas & Notes
[Add your personal thoughts here]

## 📱 Social Signal (Manual)
- **Source:** [Dropdown: Reddit/X/Instagram/GitHub Search/Other]
- **Link:** [URL]
- **Notes:** [Context]

## 📔 Journal
[Date] - [Your experiences]

---
*Source: [GitHub](https://github.com/ocrmypdf/OCRmyPDF)*
