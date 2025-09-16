# Vernus white paper

This directory contains the LaTeX sources for the Vernus white paper. It is set up to compile with LuaLaTeX using a custom engine wrapper for macOS.

## Prerequisites

- TeXShop with LuaLaTeX
- Inkscape (only if you need to regenerate the `svg-inkscape` assets)

## Using the custom LuaLaTeX engine

This project includes `lualatex-shell.engine`, a small wrapper that helps ensure a consistent LuaLaTeX invocation on macOS. If your editor supports custom engines, point it to `lualatex-shell.engine` from this directory.

## Structure overview

- `ver-white-paper.tex` - main LaTeX source for white paper
- `ver-white-paper.pdf` - white paper compiled to PDF
- `lualatex-shell.engine` — LuaLaTeX wrapper for macOS
- `fonts/` — bundled font files
- `images/` — project images (PNG/SVG/etc.)

## License

Copyright © 2025 Vernus. All rights reserved.

Vernus is a Moonka Hey Ltd. company.

Permission is granted to share this document for non-commercial informational purposes provided that the content is not altered and proper attribution ismaintained. This document does not grant any license to patents, trademarks, or other intellectual property.
