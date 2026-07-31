# 🚀 Auto GitHub Profile Contributor

Automated GitHub contribution generator configured specifically for **nitindhake3** (`178370983+nitindhake3@users.noreply.github.com`). 

This project automatically makes **20 to 30 commits daily** to keep your GitHub profile activity heatmap graph active with green contribution squares.

---

## 📁 Repository Files

- `.github/workflows/auto-commit.yml`: GitHub Actions workflow that runs automatically every day (or manually via GitHub UI) and creates a randomized batch of **20–30 commits**.
- `activity.json`: Tracks JSON status and metadata of the latest commit run.
- `contributions.log`: Appends timestamped entry logs for every single commit.

---

## 🛠️ Step-by-Step Setup Guide

Follow these exact steps to activate auto-contributions on your GitHub profile:

### Step 1: Create a New GitHub Repository
1. Go to [GitHub - New Repository](https://github.com/new).
2. Name the repository: `auto-github-contributor` (or any name you prefer).
3. Choose **Public** (or **Private** - see Step 4 if choosing Private).
4. Do **NOT** initialize with README or `.gitignore` (leave it completely empty).
5. Click **Create repository**.

### Step 2: Push This Folder to GitHub
Run the following commands in your terminal inside this folder (`C:\Users\Nitin\.gemini\antigravity-ide\scratch\auto-github-contributor`):

```bash
git init
git branch -M main
git config user.name "nitindhake3"
git config user.email "178370983+nitindhake3@users.noreply.github.com"
git add .
git commit -m "feat: initialize auto github contributor"
git remote add origin https://github.com/nitindhake3/cmitHUB.git
git push -u origin main
```

---

### Step 3: Enable Read & Write Permissions for GitHub Actions
1. Open your repository on GitHub (`https://github.com/nitindhake3/auto-github-contributor`).
2. Go to **Settings** -> **Actions** -> **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Check the box: **Allow GitHub Actions to create and approve pull requests**.
6. Click **Save**.

---

### Step 4: Ensure GitHub Profile Settings are Correct
For commits to count towards your profile graph:
1. **Noreply Email**: Using `178370983+nitindhake3@users.noreply.github.com` is GitHub's recommended privacy email format and automatically maps directly to your `nitindhake3` account!
2. **Private Contributions (If repo is Private)**:
   - Go to your public GitHub profile (`https://github.com/nitindhake3`).
   - Click **Edit profile** (or look under your contribution chart).
   - Click **Contribution settings** -> Check **Include private contributions on my profile**.

---

## 🎯 How to Run & Verify

### Automatic Execution
The GitHub Action is scheduled to run automatically **every day at 12:00 PM UTC (5:30 PM IST)**. Each run automatically generates between **20 and 30 commits** and pushes them to your `main` branch.

### Manual Instant Execution (Run 20-30 Commits Right Now)
1. Go to your GitHub repository -> Click the **Actions** tab.
2. Click **Auto GitHub Profile Contributor** on the left sidebar.
3. Click **Run workflow** dropdown on the right side.
4. Click the green **Run workflow** button.
5. Wait ~30 seconds. GitHub Actions will execute 20-30 commits!
6. Refresh your GitHub profile page (`https://github.com/nitindhake3`) to see your green squares increase!
