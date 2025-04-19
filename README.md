# Francesco Sannicola – Portfolio Website

[![Website Status](https://img.shields.io/website-up-down-green-red/https/francescosannicola.it.svg)](https://francescosannicola.it) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Welcome to the source code for my personal portfolio website, where I showcase my background, featured projects, and technical articles.

🔗 **Live Site**: [francescosannicola.it](https://francescosannicola.it)

---

## About

A lightweight, performant, and framework-free portfolio website built to highlight my skills, projects, and written articles. Designed for fast load times, maintainability, and global availability.

---

## Features

- **Modern & Responsive Design**: Adapts seamlessly across mobile, tablet, and desktop.
- **Static Content**: Pages built with plain HTML and CSS for simplicity.
- **Article & Project Showcases**: Separate directories for articles and project demos.
- **Resume Download**: Instantly download my PDF résumé.
- **CI/CD Integration**: Automated build and deployment with GitHub Actions.

---

## Performance First

This site is engineered for speed:

- 📄 **Minimal Overhead**: Pure HTML, CSS, and just enough JavaScript.
- 🌐 **Global Delivery**: Served via CloudFront with edge caching.
- 🔄 **Automatic Cache Invalidation**: New deploys purge stale content.

---

## Project Structure

```bash
├── index.html          # Homepage
├── about.html          # Personal bio and skills
├── resume.pdf          # Downloadable résumé
├── style.css           # Global stylesheet
├── assets/             # Images, icons, and media files
├── articles/           # Blog posts and write-ups
├── projects/           # Demonstration projects and case studies
└── .github/workflows/  # CI/CD pipelines (GitHub Actions)
```

---

## Deployment Workflow

1. **Push to `main`**: Any changes merged to the main branch.
2. **CI Runs**: GitHub Actions lints HTML/CSS and assets.
3. **Publish to S3**: Artifacts sync to the S3 bucket.
4. **Invalidate CDN**: CloudFront distribution is invalidated.

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/francesco-s/francescosannicola.git
   ```
2. **Serve Locally**:
   - Open `index.html` directly in your browser, or
   - Use a local server (e.g., `live-server`, `http-server`).
3. **Edit Content**:
   - Modify HTML/CSS and images files under the root and `assets/`.
   - Add new articles in the `articles/` folder.
   - Add new projects in the `projects/` folder.
4. **Deploy Updates**:
   - Push changes to `main` to trigger GitHub Actions.

---

## Contributing

Contributions are welcome! Feel free to:

- Suggest improvements via [GitHub Issues](https://github.com/francesco-s/francescosannicola/issues).
- Submit pull requests for bug fixes or enhancements.

---

## Contact

👤 **Francesco Sannicola**

- Website: [francescosannicola.it](https://francescosannicola.it)
- GitHub: [@francesco-s](https://github.com/francesco-s)
- Email: francescosannicola1997@gmail.com

Feel free to reach out for feedback, collaboration, or just to say hello!

Happy browsing! ✨
