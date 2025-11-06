# ⚙️ Set Up CI/CD Pipeline using GitHub Actions

## 🎯 Objective
Understand how to automate testing and deployment using **GitHub Actions**.  
This setup triggers workflows on every push, runs tests, and builds the React app automatically.

---

## 🧩 Folder Structure
.github/workflows/main.yml
src/
public/
package.json


---

## 🧠 Workflow Steps
| Step | Description |
|------|--------------|
| Checkout | Clone repo to GitHub runner |
| Setup Node.js | Configure Node.js environment |
| Install | Install all dependencies |
| Test | Run automated tests |
| Build | Build production-ready app |
| Upload | Save build artifacts for review |

---

## 🪜 How to Use
1️⃣ Push your code to `main` branch  
2️⃣ Go to the **Actions** tab → Watch the workflow run  
3️⃣ Wait for all ✅ green steps  
4️⃣ Check the uploaded build artifact

---

## 🧾 Expected Output
✅ Automated test + build on every push  
✅ Workflow visible in the **Actions** tab  
✅ Optionally can extend to auto-deploy (GitHub Pages / Netlify / AWS S3)

---

**🎉 You have successfully created a CI/CD pipeline using GitHub Actions!**
