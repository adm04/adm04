# 🚀 Setup Guide for Your Animated GitHub Profile (`adm04`)

Follow these simple steps to activate your animated GitHub profile README and setup automated contribution animations!

---

## 📋 Step 1: Create your Special Profile Repository

1. Log into your GitHub account: **adm04**
2. Create a new repository on GitHub:
   - **Repository name:** `adm04` (Must match your exact GitHub username `adm04`).
   - **Public / Private:** Must be **Public** (profile READMEs must be public to display on your GitHub profile page).
   - Check **Add a README file** (or push the code directly).

---

## ⚡ Step 2: Push your Files to GitHub

Initialize git and push to your `adm04/adm04` repository:

```bash
git init
git add .
git commit -m "Add animated GitHub profile README and action workflows"
git branch -M main
git remote add origin https://github.com/adm04/adm04.git
git push -u origin main
```

---

## 🔒 Step 3: Enable GitHub Actions Permissions

To allow the **Snake Animation** and **3D Contribution Graph** workflows to generate SVGs automatically:

1. Go to your repository on GitHub: `https://github.com/adm04/adm04`
2. Click on **Settings** -> **Actions** -> **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Check **Allow GitHub Actions to create and approve pull requests**.
6. Click **Save**.

---

## 🤖 Step 4: Run Workflows for the First Time

1. Go to the **Actions** tab in `https://github.com/adm04/adm04`.
2. Click on **Generate Snake Animation** on the left -> Click **Run workflow** -> **Run workflow**.
3. Click on **GitHub-Profile-3D-Contrib** on the left -> Click **Run workflow** -> **Run workflow**.

Once both run successfully (~1 minute), your Snake animation SVG will be published to the `output` branch, and the 3D graph SVG will be committed to your main branch!

---

🎉 **Congratulations!** Your GitHub profile is now animated, dynamic, and updated automatically every day!

