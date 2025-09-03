# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub Pages personal website repository hosted at crunchdomo.github.io. It's a simple static HTML site without any build process or dependencies.

## Project Structure

- `index.html` - Main webpage
- `README.md` - Repository documentation
- No package manager or build tools required

## Development

### Running Locally

To preview the site locally, you can use any static file server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if available)
npx http-server
```

Then open http://localhost:8000 in your browser.

### Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No build process is required.

## Architecture

This is a minimal static website with:
- Plain HTML files (no templating engine)
- No JavaScript framework
- No CSS framework or preprocessor
- Direct GitHub Pages hosting from the main branch

## Important Notes

- Changes to index.html will be live on crunchdomo.github.io after pushing to the main branch
- The site uses standard HTML5 structure
- Keep the HTML simple and semantic