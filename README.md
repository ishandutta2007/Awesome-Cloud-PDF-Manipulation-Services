# Awesome-Cloud-PDF-Manipulation-Services

# Top Cloud PDF Manipulation Services Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Document Processing APIs, Server-Side PDF Operations & Self-Hosted PDF Toolkits*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud PDF Manipulation Services**. These tools provide APIs and managed infrastructure for working with PDFs—merging, splitting, converting, compressing, OCR, and e-signing—so applications can handle document workflows without building low-level PDF engines from scratch.

**Examples** include Adobe PDF Services, Smallpdf, iLovePDF, CloudConvert, Sejda, PDF24, Zamzar, Apryse, and Foxit (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-transaction fees, and controlling document data. The open-source landscape is anchored by **Sejda SDK** (the AGPLv3 core behind Sejda's commercial API), **PDF.js** (Mozilla's rendering engine), **pdf-lib** (the JavaScript PDF creation/manipulation library), and **PyMuPDF** (the Python binding for MuPDF), with **Stirling-PDF** providing a full self-hosted web UI for common operations.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Adobe PDF Services API](https://developer.adobe.com/document-services/apis/pdf-services/)** | Enterprise document processing API for create, convert, combine, export, OCR, and compress operations. | **$0.05 per document transaction** after trial; enterprise packages available (e.g., 25,000 transactions for ~$2,717 via CDW) . | **6-month free trial** with transaction allowance; PDF Embed API is free . |
| **[Foxit PDF Services API](https://app.developer-api.foxit.com/pricing)** | Cloud API for conversion, merge, split, compress, and eSign with a unified credit pool. | **Startup**: **$1,750/year** (5,000 credits). **Business**: **$4,500/year** (15,000 credits). Most operations = 1 credit; envelopes = 5 credits . | No permanent free tier. Annual billing; credits reset, no rollover . |
| **[Sejda HTML to PDF API](https://www.sejda.com/developers)** | API for HTML-to-PDF conversion with self-hosted option available. | **Starter**: **$12/month** (200 req/hr, 3 concurrent). **Professional**: $24/mo. **Business**: $48/mo. **Enterprise**: $96–$768/mo . | **Free tier** for Sejda Apps (web tools) with page/hourly limits; API has no free tier . |
| **[Zamzar API](https://developers.zamzar.com/pricing)** | File conversion API covering PDF and dozens of other formats. | **Starter**: **$25/month** (500 credits, 50MB max file). **Growth**: $99/mo (2,500 credits, unlimited size). **Scale**: $299/mo (10,000 credits) . | **Test sandbox**: **100 credits**, 1MB max file, 1-day storage—for evaluation only . |
| **[CloudConvert](https://cloudconvert.com/pricing)** | File conversion API with PDF, image, video, and document format support. | **Starting at $8/month** (per Software Advice) . Tiered by conversion minutes. | Not detailed in available results. |
| **[Apryse (PDFTron)](https://apryse.com/pricing)** | Enterprise document processing SDK and API with server-side and client-side options. | **Entry-level packages from $1,500**; pricing modular based on features, volume, and deployment . | No public free tier. Custom pricing via sales . |

## Open-Source GitHub Projects

- **[Sejda SDK](https://github.com/sejda-pdf/sejda-sdk)** [![GitHub Stars](https://img.shields.io/github/stars/sejda-pdf/sejda-sdk?style=social&color=white)](https://github.com/sejda-pdf/sejda-sdk/stargazers)  
  **The open-source core behind Sejda's commercial API.** AGPLv3 licensed for open-source use—**unlimited tasks and executions** without fees . **Capabilities**: merge, split, compress, extract text, encrypt/decrypt, image-to-PDF, watermark, and header/footer operations. **Commercial caveat**: closed-source use requires a **PRO license at $2,000/year** (single task) . Best for open-source projects or teams willing to license commercially for closed-source use.

- **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** [![GitHub Stars](https://img.shields.io/github/stars/Stirling-Tools/Stirling-PDF?style=social&color=white)](https://github.com/Stirling-Tools/Stirling-PDF/stargazers)  
  **The self-hosted PDF manipulation suite.** A locally hosted web application for merging, splitting, converting, OCR, and signing PDFs—all processing stays on your infrastructure. Best for teams wanting a private, web-based PDF toolkit without per-transaction API costs.

- **[pdf-lib](https://github.com/Hopding/pdf-lib)** [![GitHub Stars](https://img.shields.io/github/stars/Hopding/pdf-lib?style=social&color=white)](https://github.com/Hopding/pdf-lib/stargazers)  
  **The JavaScript PDF creation and manipulation library.** MIT licensed. Create and modify PDFs programmatically in Node.js or the browser—embed text, images, and form fields, split/merge documents, and fill forms. Best for JavaScript/TypeScript applications needing embedded PDF generation without an external API.

- **[PyMuPDF (MuPDF)](https://github.com/pymupdf/PyMuPDF)** [![GitHub Stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social&color=white)](https://github.com/pymupdf/PyMuPDF/stargazers)  
  **The high-performance Python PDF library.** AGPL-3.0 licensed (or commercial). Bindings for MuPDF—extract text, render pages, merge/split, and manipulate PDF content with speed. Best for Python data pipelines and document processing workflows.

- **[PDF.js](https://github.com/mozilla/pdf.js)** [![GitHub Stars](https://img.shields.io/github/stars/mozilla/pdf.js?style=social&color=white)](https://github.com/mozilla/pdf.js/stargazers)  
  **The browser-based PDF rendering standard.** Apache 2.0 licensed. Mozilla's PDF viewer that renders documents in HTML5 canvas without plugins—the foundation for many web PDF viewers. Best for displaying PDFs in web applications; not a manipulation API.

### Additional Strong Open-Source Options

- **qpdf** — Command-line PDF transformation tool for encryption, linearization, and structural repair. Best for scripted batch operations.
- **pdftk** — Legacy PDF toolkit for merge/split/forms. Best for simple scripted workflows.
- **Docling (IBM)** — Document conversion library with PDF parsing and structure extraction. Best for AI/RAG pipelines needing PDF-to-structured-text.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **SaaS pricing is per-transaction and opaque**: Adobe charges **$0.05 per document transaction** after trial ; Foxit bundles credits into annual plans starting at **$1,750/year** ; Apryse starts at **$1,500** but requires sales engagement for actual quotes .
- **Free tiers are for evaluation, not production**: Zamzar's sandbox caps at **100 credits and 1MB files** ; Sejda's free tier applies to its web apps, not the API . None of the API-focused services offer a permanent free production tier.
- **Sejda SDK is AGPLv3**: open-source use is free with unlimited tasks, but **closed-source commercial use requires a $2,000/year PRO license** . Verify licensing compatibility before deploying.
- **Self-hosted toolkits require infrastructure**: Stirling-PDF, pdf-lib, and PyMuPDF all need servers or application integration—free software is not free operations.

---

**Made for developers, document engineers, and organizations building PDF processing pipelines.**  
Let's make cloud PDF manipulation more open, transaction-transparent, and self-hostable.
