# Slides

A centralized repository containing slide decks and talks.

---

## Overview

This repository uses [Quarto](https://quarto.org/?utm_source=gemini) with the
[Reveal.js](https://revealjs.com/?utm_source=gemini) framework to generate
interactive, web-native slide presentations directly from plain-text Markdown
(`.qmd`) files.

Each talk lives in its own dedicated, chronologically named directory using the
following convention:

```text
YYYY-MM-DD-event-name/

```

---

## Working with Presentations

Navigate to the specific presentation folder before running commands:

```bash
cd 2026-09-23-icam

```

### Live Preview (Development)

To launch a local web server with hot-reloading (updates automatically as you
save your `.qmd` file in Emacs or your editor):

```bash
quarto preview slides.qmd

```

### Render to HTML

To build the final standalone presentation deck without launching a local
server:

```bash
quarto render slides.qmd

```

The output will be an HTML file (e.g., `slides.html`) that can be opened
directly in any modern browser.


```
