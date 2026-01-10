# 🚀 30 Days of JavaScript Challenge

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=30+Days+of+JavaScript+Challenge;Build+Strong+Foundations;Daily+Progress+%7C+Practical+Exercises;Modern+JavaScript+Techniques" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/your-username/30-days-javascript?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/your-username/30-days-javascript?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/your-username/30-days-javascript?style=for-the-badge" />
</p>

---

## 📌 About the Challenge

This **30 Days of JavaScript Challenge** is a structured learning journey designed to:

* ✅ Build **strong JavaScript fundamentals**
* ✅ Improve **problem‑solving skills**
* ✅ Practice **modern ES6+ techniques**
* ✅ Track **daily progress with hands‑on exercises**

Each day focuses on a specific concept with practical coding tasks and mini‑challenges.

---

## 🧠 What You'll Learn

```txt
✔ JavaScript Basics
✔ Control Flow & Loops
✔ Functions & Scope
✔ Arrays & Objects
✔ DOM Manipulation
✔ Events & Forms
✔ ES6+ Features
✔ Asynchronous JavaScript
✔ APIs & Fetch
✔ Mini Projects
```

---

## 🗂️ Challenge Structure

```bash
📦 30-Days-JavaScript
 ┣ 📂 Day-01  Basics & Setup
 ┣ 📂 Day-02  Variables & Data Types
 ┣ 📂 Day-03  Operators & Conditions
 ┣ 📂 Day-04  Loops
 ┣ 📂 Day-05  Functions
 ┣ 📂 Day-06  Arrays
 ┣ 📂 Day-07  Objects
 ┣ 📂 Day-08  DOM Basics
 ┣ 📂 Day-09  Events
 ┣ 📂 Day-10  Mini Project
 ┣ 📂 ...
 ┗ 📂 Day-30  Final Project
```

---

## 📅 Daily Progress Tracker

| Day | Topic                  | Status |
| --- | ---------------------- | ------ |
| 01  | JavaScript Basics      | ✅      |
| 02  | Variables & Data Types | ✅      |
| 03  | Conditions             | 🔄     |
| 04  | Loops                  | ⏳      |
| ... | ...                    | ...    |
| 30  | Final Project          | ⏳      |

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=your-username&theme=react-dark" />
</p>

---

## ⚙️ Technologies Used

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,html,css,git,github,vscode" />
</p>

---

## 🎯 Goals

* 📈 Code **every day for 30 days**
* 🧩 Solve real‑world problems
* 🛠 Build mini projects
* 🧠 Gain confidence in JavaScript

---

## 🧪 Example Challenge (Day 01)

```js
// Print numbers from 1 to 10
for (let i = 1; i <= 10; i++) {
  console.log(i);
}
```

---

## 🌟 Motivation

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" />
</p>

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a pull request

---

## ⚡ GitHub Actions Progress Animation

This repository uses **GitHub Actions** to automatically track daily progress and keep the README fresh and engaging.

### 🔄 Workflow Features

* ✅ Auto-updates progress badges
* 📅 Tracks daily commits
* 📊 Refreshes activity graph
* 🚀 Encourages consistency streaks

<p align="center">
  <img src="https://github.com/your-username/30-days-javascript/actions/workflows/progress.yml/badge.svg" />
</p>

### 📁 GitHub Actions Workflow

Create the following file in your repository:

```bash
.github/workflows/progress.yml
```

```yaml
name: Update Progress

on:
  push:
    branches: [ main ]
  schedule:
    - cron: "0 0 * * *"

jobs:
  update-readme:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Update progress timestamp
        run: |
          echo "Last updated: $(date)" > progress.txt

      - name: Commit changes
        run: |
          git config --global user.name "github-actions"
          git config --global user.email "github-actions@github.com"
          git add .
          git commit -m "chore: update daily progress" || exit 0
          git push
```

> 🔥 This workflow runs **daily** and on every push, creating a living, animated repository.

---

## 📬 Connect With Me

<p align="center">
  <a href="https://github.com/your-username"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github" /></a>
  <a href="https://linkedin.com/in/your-profile"><img src="https://www.linkedin.com/in/eman-fatima-64aa8a271/" /></a>
  <a href="https://twitter.com/your-handle"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter" /></a>
</p>

---

<p align="center">
  🔥 <strong>Consistency beats motivation. See you on Day 30!</strong> 🔥
</p>
.
