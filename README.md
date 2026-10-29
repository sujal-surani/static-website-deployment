# Cloud & DevOps Engineer Portfolio

A lightweight, static portfolio website built with HTML and CSS, deployed continuously using GitHub Pages. This repository serves as a showcase of my skills, projects, and cloud architecture experience.

## Live Demo

🌐 [**View the live website here**](https://sujal-surani.github.io/static-website-deployment/)

## Project Overview

The portfolio is built using native web technologies without heavy frameworks to ensure maximum performance and simplicity. It features a clean, responsive layout structured into the following sections:

* **About Me:** Background and focus on Cloud Architecture, IaC, and terminal-first workflows.
* **Technical Skills:** Outlining proficiency in AWS, Terraform, Docker, Kubernetes (k3s), and Linux administration.
* **Featured Projects:** Highlighting serverless deployments like the Serverless Survey API and Project Nexus (DevSecOps API Pipeline).
* **Connect:** Direct links to my GitHub and LinkedIn profiles.

## Tech Stack

* **Markup:** HTML5 (Semantic Structure)
* **Styling:** CSS3 (Custom Dark Theme, CSS Variables)
* **Version Control:** Git
* **Hosting & CI/CD:** GitHub Pages

## Deployment Architecture

This site utilizes GitHub Pages for free, reliable static hosting. The deployment workflow is entirely GitOps-driven:

1. Local changes are committed to the `main` branch.
2. Code is pushed to the remote GitHub repository.
3. GitHub Actions automatically triggers a background build and deployment workflow.
4. The static assets are served directly from GitHub's CDN to the live URL.

## Local Development

To view or modify this project locally on your machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/sujal-surani/static-website-deployment.git
   ```

2. Navigate into the directory:
   ```bash
   cd static-website-deployment
   ```

3. Open `index.html` in your preferred web browser. No local web server is strictly required for these static files, though you can use tools like Live Server in VS Code for hot-reloading during development.

---
*Created by Sujal Surani*