# 🚀 First Node.js Jenkins Pipeline

This is a **minimal Node.js project** to demonstrate how Jenkins pipelines work with **Docker agents** and **GitHub integration**.

---

## 📌 Pipeline Overview
The Jenkins pipeline (`Jenkinsfile`) runs inside a **Node.js Docker container** (`node:16-alpine`) and performs:

1. **Checkout** - Clones the GitHub repository  
2. **Install Dependencies** - Runs `npm install`  
3. **Run Tests** - Executes `npm test` 
4. **Build** - Simulates a build step with `npm run build`
