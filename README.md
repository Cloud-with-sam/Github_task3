# DevOps Task 3 – Version-Controlled Project with Git & GitHub
## 🚀 Overview
This repository is part of DevOps Task 3 and demonstrates a basic version-controlled project setup using Git and GitHub. The goal is to showcase:

- Git branching strategy (main → dev → feature)
- Pull request workflows
- Commit history
- Tagging a release
- Markdown documentation and proper repo hygiene

---

## 🏗️ Project Structure

devops-task3/
├── hello.py # Simple sample Python script
├── README.md # This file
├── .gitignore # Ignore list for Git
└── tasks.md # List of actions performed

yaml
Copy code

---

## 🔨 What Was Done

- Initialized Git repo locally and connected it to GitHub
- Created and pushed 3 branches:
  - main
  - dev
  - feature/add-hello
- Created a basic Python app (hello.py)
- Made PR: feature → dev → main
- Tagged the final version as `v1.0`
- Wrote documentation (README, tasks.md)
- Added a .gitignore file
---
## 🧪 How to Run the App

You can run the sample Python script by executing:

```bash
python3 hello.py
It should output:

Copy code
Hello, DevOps!
🌱 Branching Workflow
Branch	Purpose
main	Stable release branch
dev	Development integration branch
feature/add-hello	Feature branch for adding hello.py

Feature branches are merged into dev using pull requests.

Dev is merged into main after integration testing via PR.

📦 Tagging and Release
An annotated tag was created to mark the deliverable:

bash
Copy code
git tag -a v1.0 -m "v1.0 - initial deliverable"
git push origin v1.0
You can view this under the "Tags" or "Releases" section of the repo.

📄 Supporting Files
.gitignore – prevents committing unnecessary files like node_modules, pycache, .env, etc.

tasks.md – a markdown log of actions taken during this task.

✅ Task Submission
This repo satisfies all requirements of Task 3. It includes:

Branches: main, dev, and feature

Pull requests and merge history

Tag for release

Documentation files

A working app file (hello.py)

✔️ GitHub Repo Link: https://github.com/Cloud-with-sam/Github_task3

<img width="1918" height="1079" alt="Screenshot 2025-09-26 131219" src="https://github.com/user-attachments/assets/0c9fc144-ecb8-42f2-8308-30ccdf368891" />
<img width="1919" height="1079" alt="Screenshot 2025-09-25 213849" src="https://github.com/user-attachments/assets/612208eb-d1b7-44bd-845c-1828ba802607" />
<img width="1918" height="1079" alt="Screenshot 2025-09-25 213155" src="https://github.com/user-attachments/assets/7317dc00-dd67-483d-a30a-d8e5f63edc11" />

