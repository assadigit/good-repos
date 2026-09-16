---
source: https://github.com/booklore-app/booklore
aliases:
  - booklore
  - booklore-app/booklore
tags: [java, java, spring-boot, self-hosted, ebooks, opds, angular, book-management, library-management-system, metadata-management, oidc, typescript]
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

> **TL;DR:** Self-hosted multi-user digital library with smart shelves, auto metadata, Kobo/KOReader sync, OPDS, and built-in EPUB/PDF/comic reader.

**`booklore-app/booklore`** · ⭐ 861 · 🔧 Java

## What is it?
BookLore is a self-hosted, multi-user digital library application that centralizes your entire book collection in one place. It supports organizing, reading, annotating, syncing across devices, and sharing books without relying on third-party services. The platform handles EPUB, PDF, and comic file formats with a built-in browser-based reader.

Key capabilities include rule-based "Magic Shelves" for dynamic organization, automatic metadata enrichment from Google Books, Open Library, and Amazon, and full-text search. It integrates with Kobo e-readers, KOReader, and any OPDS-compatible app for seamless device sync. A "BookDrop" feature watches a folder and automatically detects, enriches, and queues new files for import.

The system supports multiple users with individual shelves, reading progress, and preferences, secured via local or OIDC authentication. It is built with a Spring Boot (Java) backend and Angular frontend.

## How does it work?
BookLore runs as a self-hosted Spring Boot (Java) server with an Angular single-page frontend. The backend handles book storage, metadata enrichment via external APIs (Google Books, Open Library, Amazon), user management with OIDC support, and protocol integrations (OPDS for ebook sharing, Kobo/KOReader sync). The BookDrop feature uses folder watching to auto-detect new ebook files, enrich them with metadata, and queue them for import.

The built-in reader renders EPUB, PDF, and comic files directly in the browser, supporting annotations, highlights, and reading progress tracking. Smart Shelves use rule-based logic to dynamically organize books, while OPDS endpoints allow any compatible app to browse and sync the library.

## Why is it important? (Core Value)
For a software engineer interested in self-hosted alternatives to SaaS products, BookLore is a strong candidate as a self-hosted replacement for services like StoryGraph, Goodreads, or Calibre-Web. It eliminates dependency on third-party ebook ecosystems (Amazon, Apple Books) while providing enterprise-grade features like OIDC authentication and multi-user support. The OPDS and Koko/KOReader integrations make it a practical homelab solution for managing a family or team digital library. The BookDrop folder-watching pattern is a clean automation approach for ingestion workflows.

## Key Features & Technologies
- Spring Boot (Java) backend with Angular frontend
- Built-in browser reader for EPUB, PDF, and comics with annotations
- Automatic metadata enrichment from Google Books, Open Library, and Amazon
- Kobo, KOReader, and OPDS-compatible device sync
- Multi-user support with OIDC authentication
- BookDrop folder-watching for automated import and enrichment
- Rule-based Magic Shelves with full-text search

## Difference from Others
Unlike Calibre-Web, which focuses primarily on cataloging and serving EPUBs via OPDS, BookLore adds a full browser-based reader with annotations and reading progress, plus native Kobo/KOReader sync. Compared to StoryGraph or Goodreads, it is fully self-hosted with no third-party dependency and supports multi-user with OIDC. The combination of Magic Shelves (rule-based dynamic organization), BookDrop auto-import, and multi-format reading (EPUB, PDF, comics) in a single self-hosted package distinguishes it from point solutions like calibre or standalone readers.

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
