# 🚀 GitHub Actions Deployment Workflow

This project is a part of the **GitHub Pages Deployment** challenge from [roadmap.sh](https://roadmap.sh/projects/github-actions-deployment-workflow). The main objective of this project is to understand and implement the core concepts of **CI/CD (Continuous Integration / Continuous Deployment)**.

---

## 🎯 Project Goal
To automate the deployment process using GitHub Actions. Whenever a change is pushed to the `index.html` file on the `main` branch, the workflow automatically triggers and deploys the updated static website to **GitHub Pages** without any manual intervention.

---

## 🛠️ Tech Stack
* **HTML5** - To build the simple static webpage.
* **GitHub Actions** - To orchestrate the automated CI/CD deployment pipeline.
* **GitHub Pages** - To host the static website for free.

---

## ⚙️ How the Workflow Works
The configuration file `.github/workflows/deploy.yml` handles the automation based on specific conditions:
1. **Target Branch:** It only triggers on a `push` event targeting the `main` branch.
2. **Path Filtering (`paths`):** The workflow executes **only** when changes are made to the `index.html` file. Modifying other files (like `README.md`) will not trigger a deployment, optimizing server resource usage.

---

## 🚀 Live Demo
The automated deployment pipeline is fully functional! You can view the live website here:

👉 **[View the Live Website](https://nilcodes16.github.io/gh-deployment-workflow/)**

---

## 🧠 Key Takeaways
* Learned how to configure and write a GitHub Actions workflow using YAML syntax.
* Understood how to restrict workflow triggers using path-filtering (`paths:`).
* Gained practical hands-on experience with modern DevOps automation and cloud hosting.
