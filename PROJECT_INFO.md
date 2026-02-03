# EduDocs Project

## Goal
Demonstrate how to implementation and deploy a Docsify-based documentation site focused on educational purposes.

## Tech Stack
- **Docsify v4**: Magical documentation generator.
- **docsify-themeable**: Premium theme system.
- **Markdown**: Content format.
- **CDN**: JS Delivr (for loading assets).

## Setup & Run Instructions
1. Navigate to the project folder.
2. Serve the files using any local server:
   - Python: `python3 -m http.server 3000`
   - Node: `npx docsify-cli serve .`
3. Open `http://localhost:3000` in your browser.

## Deployment
This project can be deployed to:
- **Cloudflare Pages**: Connect your GitHub repo, set build command to *empty*, and directory to `./`.
- **GitHub Pages**: Go to Settings > Pages and select the branch and folder (`/`).

## History
- **v1.0**: Initial setup with Premium theme, search plugin, and educational content.
