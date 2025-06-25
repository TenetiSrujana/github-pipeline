# GitHub Actions Pipeline - Node.js CI

This repo demonstrates a simple **GitHub Actions** workflow that sets up a Node.js environment and logs a personalized message.

---

##  What it does

- Runs on every push or pull request to the `main` branch  
- Sets up Node.js (v18) on Ubuntu latest  
- Prints a custom greeting message:  
  `Hello from @TenetiSrujana`

---

##  How it works

The workflow is defined in `.github/workflows/main.yml` and does the following:

1. Checks out the repository code  
2. Sets up Node.js environment  
3. Runs a script to echo a custom message with your GitHub username

---

##  How to use

1. Clone the repo  
2. Push any changes to the `main` branch  
3. Go to the **Actions** tab on GitHub to see the workflow running  
4. Check the logs for the greeting message!

---

##  Purpose

This project helps you learn:

- GitHub Actions workflow creation  
- Setting up Node.js in CI/CD pipelines  
- Automating simple tasks with YAML configs

---

##  Author

[@TenetiSrujana](https://github.com/TenetiSrujana)

---
## Workflow Run Screenshot

Here's a screenshot of the GitHub Actions pipeline running smoothly:

<img width="1470" alt="Screenshot 2025-06-25 at 11 34 21 AM" src="https://github.com/user-attachments/assets/6a507ab5-c4d0-4313-befa-2a0e7e8c3b74" />
<img width="1470" alt="Screenshot 2025-06-25 at 11 31 19 AM" src="https://github.com/user-attachments/assets/30dd5f15-f59e-4835-85ed-d6985ca623fd" />
