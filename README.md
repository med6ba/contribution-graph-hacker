# 🟩 GitHub Contribution Graph Hacker

## 🚀 Overview
This project automates Git commits to create a custom pattern on your GitHub contribution graph. By running a script, you can generate a visually appealing commit history.

## ⚠️ Disclaimer
This project is for educational purposes only. Abusing GitHub's contribution system may violate their policies. Use responsibly.

## 📌 Features
- Automates commits for specific days.
- Customizable commit patterns.
- Works with multiple repositories.

## 📦 Dependencies
- Node.js (latest LTS recommended)

- Git and GitHub repository (public or private)

- moment – Handles date and time manipulation.

- simple-git – Runs Git commands seamlessly.

- random – Generates random numbers for commit distribution.

## 🛠️ Getting Started
1️⃣ Clone the repo:
```sh
git clone https://github.com/med6ba/contribution-graph-hacker.git
cd contribution-graph-hacker
```

2️⃣ Initialize your Node.js project:
```sh
npm init -y  
```

3️⃣ Install dependencies:
```sh
npm install moment simple-git random
```
4️⃣ Customize your commit script:

Open `config.json` and customize your commit schedule.

5️⃣ Run the script to start generating commits:

```sh
node index.js
```

## ©️ Credits
Original project by <a href="https://github.com/fenrir2608/goGreen">fenrir2608</a>. All rights belong to the original author. This repository is a modification of the original work.
