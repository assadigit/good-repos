---
source: "https://github.com/Stirling-Tools/Stirling-PDF"
aliases:
  - Stirling-PDF
  - Stirling-Tools/Stirling-PDF

tags: [typescript, java, pdf, self-hosted, docker, document-processing, pdf-converter, pdf-manipulation, pdf-merger, pdf-tools, pdf-web-apps, pdf-ocr]
category: "Media"
stars: 92326
org: "Stirling-Tools"
primary_language: TypeScript
languages: [TypeScript, Java, Python, CSS, Shell]
credibility_score: 72.0/100
date_processed: 2026-09-16
last_release: 2026-08-06
cover: attachments/banners/Stirling-PDF_banner.png

---

![banner](attachments/banners/Stirling-PDF_banner.png)

# Stirling-PDF

> **TL;DR:** Self-hosted open-source PDF platform with 50+ tools for editing, converting, signing, and automating PDFs via web UI or private API.

**`Stirling-Tools/Stirling-PDF`** · ⭐ 92,326 · 🔧 TypeScript

## What is it?
Stirling-PDF is a powerful, open-source PDF editing platform that consolidates over 50 PDF manipulation tools into a single application. It can be run as a personal desktop app, accessed through a browser, or deployed on your own servers with a private API. The platform covers the full PDF lifecycle: editing, merging, splitting, signing, redacting, converting formats, OCR, compression, and more.

With over 92,000 GitHub stars and 8,500+ forks, it is the most popular PDF application on GitHub. It emphasizes data privacy by keeping all document processing local—no PDFs are ever sent to external services. The project supports Docker deployment and is built in Java, making it suitable for enterprise or homelab environments where document handling must remain within your infrastructure.

The platform also includes automation and workflow capabilities, allowing users to chain PDF operations together programmatically through its private API, which makes it more than a simple web UI—it functions as a self-hosted PDF microservice.

## How does it work?
Stirling-PDF is built in Java and deployed primarily via Docker, exposing a web-based dashboard and a private REST API. The application runs entirely on your own hardware or cloud instance, processing all PDF operations locally so documents never leave your network. It exposes capabilities like format conversion (PDF to Word, images, etc.), OCR for scanned documents, merging/splitting pages, digital signing, redaction, compression, and batch automation through its API.

Architecturally, it operates as a self-hosted web service: the Docker container bundles the Java backend, web UI, and all 50+ PDF processing tools. Users interact via the browser dashboard for one-off tasks or via the private API for programmatic, automated workflows. This makes it functionally equivalent to a SaaS PDF service (like Smallpdf or ILovePDF) but entirely under your control.

## Why is it important? (Core Value)
For a software engineer and researcher focused on self-hosted alternatives and automation, Stirling-PDF is a direct replacement for SaaS PDF services that typically require uploading documents to third-party servers. Its private API means you can integrate PDF processing (conversion, OCR, merging) into your own automation pipelines without external dependencies—exactly the kind of self-hostable tool that fits into a homelab or CI/CD workflow. The 50+ tools in one container eliminate the need for multiple disparate PDF utilities, and the Docker deployment model makes it trivially deployable alongside other self-hosted services you already run.

The automation and workflow features are particularly relevant to your interest in workflow orchestration: you can script batch PDF operations (e.g., convert a folder of scanned documents via OCR, merge them, compress, and output) through the API without any manual steps. This positions Stirling-PDF as both a practical daily tool and a composable service in a larger automation stack.

## Key Features & Technologies
- 50+ built-in PDF tools (edit, merge, split, sign, redact, convert, OCR, compress)
- Self-hosted deployment via Docker with private REST API
- Runs as desktop app, browser UI, or headless server
- Java-based backend with full document processing pipeline
- Automation and workflow chaining for batch PDF operations
- No external data transfer—all processing stays local

## Difference from Others
Unlike single-purpose PDF tools (e.g., a converter or a merger), Stirling-PDF consolidates the entire PDF toolchain into one self-hosted platform with a unified API. Compared to SaaS alternatives like Smallpdf or ILovePDF, it eliminates data privacy concerns and vendor lock-in by keeping all processing on your infrastructure. Versus lightweight CLI tools (like qpdf or pdftk), it adds a full web dashboard, digital signing, OCR, and batch automation—making it suitable for non-technical users while still offering programmatic access. Its 92K+ stars and active community signal long-term viability that smaller PDF utilities lack.

## 🏢 Organization & Credibility
- **Developer:** Stirling-Tools
- **Reputation:** Unknown
- **Stars:** 92,326
- **Forks:** 8578
- **Recent Activity:** 741 commits in 3 months
- **Credibility Score:** 72.0/100 (Average)
- **Languages:** TypeScript, Java, Python, CSS, Shell
- **Last Release:** 2026-08-06
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
*Source: [GitHub](https://github.com/Stirling-Tools/Stirling-PDF)*
