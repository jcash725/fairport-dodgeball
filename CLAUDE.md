# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Fairport Dodgeball, built as a single HTML file with embedded CSS and JavaScript. It's a "coming soon" landing page for a dodgeball league/organization.

## Architecture

- **Single-file structure**: The entire website is contained in `index.html` (~1200 lines)
- **Embedded styles**: All CSS is written inline within `<style>` tags in the HTML head
- **Vanilla JavaScript**: All interactivity is handled with plain JavaScript at the bottom of the HTML file
- **Static assets**: Images are stored in the `assets/` directory
- **No build process**: This is a static HTML website that can be served directly

## File Structure

```
├── index.html          # Main website file (contains HTML, CSS, and JS)
├── index.html.backup   # Backup copy
└── assets/             # Static assets
    ├── hero-background.jpg
    ├── image-2.png
    └── image-3.png
```

## Development

Since this is a static HTML file with no build process:

- **Local development**: Open `index.html` directly in a browser or use any local web server
- **No package manager**: No npm, yarn, or other package management
- **No build step**: No compilation, bundling, or preprocessing required
- **Direct editing**: Modify `index.html` directly for all changes

## Code Organization within index.html

The file is structured as:
1. HTML head with meta tags and embedded CSS (lines 1-800+)
2. HTML body with page content and structure
3. Embedded JavaScript for interactivity at the bottom

## Common Tasks

- **Preview changes**: Open `index.html` in a browser
- **Deploy**: Upload `index.html` and `assets/` folder to any web server
- **Backup**: Copy `index.html` before making changes (backup already exists as `index.html.backup`)

## Key Features

- Responsive navigation with mobile menu toggle
- Smooth scrolling between sections
- Contact form (frontend-only, no backend processing)
- Multiple sections: hero, about, programs, contact