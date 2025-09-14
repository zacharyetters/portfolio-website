# Portfolio Website

This repository contains the source code for my personal portfolio website that I built with Hugo and the Blowfish theme.

![website](content/projects/2023-12-portfolio-website/portfolio-theme-v3.png)


## Features
- Showcases my professional projects and technical case studies
- Includes a detailed About page
- Highlights my publications and writing
- Custom CSS for a unique look and feel
- Responsive design for all devices
- Built for speed and security with Hugo and Cloudflare

## Technologies Used
- [Hugo](https://gohugo.io/)
- [Blowfish](https://blowfish.page/)
- HTML and CSS

## Repository Structure
```
archetypes/         # Archetype templates for new content
assets/             # Custom CSS, images, and other assets
config/             # Hugo configuration files
content/            # Main site content (pages, projects, etc.)
data/               # Data files (if any)
i18n/               # Internationalization files
layouts/            # Custom layouts and partials
public/             # Generated static site (output)
static/             # Static files (favicon, manifest, etc.)
themes/             # Hugo themes (Blowfish)
```

## Build Locally
1. [Install Hugo](https://gohugo.io/installation/)
2. Clone this repository:
   ```sh
   git clone https://github.com/zacharyetters/portfolio-website.git
   cd portfolio-website
   ```
3. Start the local development server:
   ```sh
   hugo server -FD
   ```
4. Visit `http://localhost:1313` in your browser.

## Deployment
I use [Cloudflare Workers](https://workers.cloudflare.com/) to deploy and serve this website globally with high performance and security. The static site is built with Hugo and the output in the `public/` directory is automatically uploaded to Cloudflare's edge network using a CI/CD workflow.

## License

The code in this repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

All written content (including articles, case studies, and documentation) and all images are copyright © Zachary Etters. These may not be reproduced, distributed, or used without explicit permission.
