# Agent Guidelines for benoitmartin88.github.io

This document outlines the conventions and commands for agents operating within this repository, which is a Hugo site using the Blowfish theme.

## 1. Build, Lint, and Test Commands

Agents should use the following commands for standard operations:

| Task | Command | Notes |
| :--- | :--- | :--- |
| **Build Site** | `hugo --minify` | Generates the production-ready static site in `/public`. |
| **Check Translations** | `node themes/blowfish/genLangLinks.js` | Useful for verifying language link generation. |
| **Run Single Test** | N/A | Hugo does not have a dedicated unit testing framework. Verify changes by running a full build and checking for console errors. |

## 2. Code Style and Conventions

### General
- **File Structure:** Content resides in `content/`, configuration in `site/config/`, and theme files are in `themes/blowfish/`.
- **Configuration:** Primary configuration is in TOML files under `site/config/_default/`.

### Content & Markdown
- **Content Files:** Use `.md` files in `content/`. Front Matter must be valid YAML or TOML (check surrounding files).
- **Images:** Place site-wide assets in `site/assets/img/`. Theme assets are in `themes/blowfish/assets/img/`.

### Styling & Types
- **CSS:** Styling is primarily managed via Tailwind CSS configuration within the theme (`themes/blowfish/tailwind.config.js`). Direct CSS edits should target `site/assets/css/custom.css` if necessary.
- **Types:** This is a static site generator; no explicit TypeScript/Flow types are enforced outside of any Node.js scripts.

### Naming & Imports
- **Go/Hugo:** Follow standard Go naming conventions for partials and shortcodes.
- **Node.js Scripts:** Follow standard JavaScript/Node.js conventions.

### Error Handling
- **Build Errors:** Any error during `hugo` execution must be treated as a critical failure.
- **Node Scripts:** Ensure any executed Node scripts run to completion without throwing unhandled exceptions.

### Agent-Specific Rules
- **Cursor Rules:** No specific `.cursor/rules/` files found.
- **Copilot Rules:** No `.github/copilot-instructions.md` file found.
