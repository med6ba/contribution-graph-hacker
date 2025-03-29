# 🟩 GitHub Contribution Graph Hacker

## 🚀 Overview  
This project automates Git commits to generate custom patterns on your GitHub contribution graph. Run a script to create an eye-catching commit history effortlessly.

## ⚠️ Disclaimer  
This project is for educational purposes only. Misusing GitHub’s contribution system could violate their policies. Use responsibly.

## 📌 Features  
- ✅ Automates commit creation for selected dates.  
- ✅ Allows custom commit patterns.  
- ✅ Supports multiple repositories.

## 📦 Dependencies  
- **Node.js** (Latest LTS recommended)  
- **Git** (Installed) and a **GitHub repository** (public or private)  
- **moment** – Handles date and time manipulation.  
- **simple-git** – Runs Git commands seamlessly.  
- **random** – Generates random numbers for commit distribution.

## 🛠️ Getting Started

1️⃣ **Clone the repo:**
    <br>
    ```
    git clone https://github.com/med6ba/contribution-graph-hacker.git
    ```
    <br>
    ```
    cd contribution-graph-hacker
    ```

2️⃣ **Initialize your Node.js project:**
    ```
    npm init -y
    ```

3️⃣ **Install dependencies:**
    ```
    npm install moment simple-git random
    ```

4️⃣ **Customize your commit script:**  
   - Open `config.json` and modify the schedule to define commit frequency and patterns.

5️⃣ **Run the script to start generating commits:**
    ```
    node index.js
    ```

## ©️ Credits  
Based on the original project by <a href="https://github.com/fenrir2608/goGreen">**fenrir2608**</a>.
