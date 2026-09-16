---
source: https://github.com/booklore-app/booklore
aliases:
  - booklore
  - booklore-app/booklore
tags: [java, self-hosted, ebooks, java, spring-boot, angular, book-management, library-management-system, metadata-management, oidc, opds, typescript]
category: Backend
stars: 861
org: booklore-app
primary_language: Java
languages: [Java, TypeScript, HTML, SCSS, JavaScript]
credibility_score: 42.0/100
date_processed: 2026-08-19
last_release: 2026-06-26
cover: attachments/banners/booklore_banner.png

---

![banner](attachments/banners/booklore_banner.png)

# booklore

> **TL;DR:** Self-hosted multi-user digital library with smart shelves, auto metadata, Kobo/KOReader sync, and built-in EPUB/PDF reader.

**`booklore-app/booklore`** · ⭐ 861 · 🔧 Java

## What is it?
BookLore is a self-hosted, multi-user digital library application that consolidates an entire book collection into a single, locally-controlled platform. It lets users organize books with smart shelves, read EPUBs, PDFs, and comics directly in the browser, annotate content, and sync reading progress across devices via Kobo, KOReader, or any OPDS-compatible app. The system supports multiple users with individual shelves, progress tracking, and preferences, authenticated via local accounts or OIDC.

Key capabilities include automatic metadata enrichment (covers, descriptions, reviews, ratings) from Google Books, Open Library, and Amazon; rule-based 'Magic Shelves' that auto-organize books; a watched-folder import system called BookDrop that detects, enriches, and queues new files; and one-click sharing of books and shelves. The project is built with Angular on the frontend and Spring Boot (Java) on the backend, making it a full-stack self-hosted solution.

The project targets users who want full ownership and control over their book collections without depending on proprietary services like Amazon Kindle or Apple Books, offering a private, network-agnostic alternative that works across devices and users.

## How does it work?
BookLore is a full-stack web application with an Angular single-page frontend and a Spring Boot (Java) backend. The backend handles book storage, metadata enrichment via third-party APIs (Google Books, Open Library, Amazon), user authentication (local or OIDC), and the OPDS protocol for device synchronization. The BookDrop feature watches a designated folder for new files, automatically detects them, pulls metadata, and queues them for import into the library. Smart Shelves use rule-based logic to dynamically categorize and organize books, while the built-in reader renders EPUB, PDF, and comic formats in the browser with annotation and progress tracking. Device sync integrates with Kobo e-readers, KOReader, and any OPDS-compatible client so reading progress and library state follow the user across devices.

## Why is it important? (Core Value)
For this user, BookLore directly addresses the objective of finding self-hostable alternatives to SaaS products and the interest in homelab infrastructure. It provides a complete, self-hosted replacement for proprietary ebook ecosystems (Kindle, Apple Books) that are locked to vendor clouds. The multi-user OIDC support makes it suitable for a homelab setup where multiple family members or team members can have individual libraries under a single deployment. The user's interest in developer productivity and automation is served by the BookDrop auto-import pipeline and the OPDS integration, which enables programmatic access to the library. As a Spring Boot + Angular project, it also serves as a reference implementation for building self-hosted multi-user web services with modern frontend/backend separation.

## Key Features & Technologies
- Smart Shelves with rule-based Magic Shelves, filters, and full-text search
- Automatic metadata enrichment from Google Books, Open Library, and Amazon
- Built-in browser reader for EPUB, PDF, and comics with annotations and highlights
- Kobo, KOReader, and OPDS device sync for cross-device reading progress
- Multi-user support with local or OIDC authentication and per-user shelves
- BookDrop watched-folder import with auto-detect, enrich, and queue pipeline
- Full-stack architecture: Angular frontend + Spring Boot (Java) backend

## Difference from Others
Unlike Calibre (desktop-centric, single-user, no built-in web reader) or Cal-Web (limited web interface, no multi-user support), BookLore is a purpose-built, multi-user, browser-native library that includes a full reading experience, device sync via Kobo/KOReader/OPDS, and OIDC authentication out of the box. Compared to proprietary services like Amazon Kindle or Apple Books, it is fully self-hosted and vendor-agnostic. The combination of rule-based Magic Shelves, one-click sharing, and the BookDrop auto-import pipeline distinguishes it from generic file-storage or simple ebook server projects, positioning it as a complete digital library platform rather than a single-purpose tool.

## 🏢 Organization & Credibility
- **Developer:** booklore-app
- **Reputation:** Unknown
- **Stars:** 861
- **Forks:** 66
- **Recent Activity:** 10 commits in 3 months
- **Credibility Score:** 42.0/100 (Low)
- **Languages:** Java, TypeScript, HTML, SCSS, JavaScript
- **Last Release:** 2026-06-26
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
*Source: [GitHub](https://github.com/booklore-app/booklore)*
