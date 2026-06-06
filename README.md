# GitHub Profile README — Setup Instructions

## Folder Structure

```
rijulnambiar/              ← Your GitHub profile repository (same name as your username)
├── README.md              ← The main profile README (provided)
└── .github/
    └── workflows/
        └── snake.yml      ← GitHub Actions workflow (provided)
```

---

## Step 1 — Create Your Profile Repository

1. Go to https://github.com/new
2. Set the repository name to exactly: `rijulnambiar`
   (It must match your GitHub username exactly)
3. Check ✅ **Public**
4. Check ✅ **Add a README file**
5. Click **Create repository**

---

## Step 2 — Add the README

1. Open the repository you just created
2. Click the pencil ✏️ icon on README.md to edit
3. Delete all existing content
4. Paste the entire content from `README.md` (provided)
5. Commit changes

---

## Step 3 — Set Up Snake Contribution Graph

1. In your profile repo, create the folder path: `.github/workflows/`
2. Create a new file called `snake.yml` inside it
3. Paste the content from `snake.yml` (provided)
4. Commit the file

**Enable Actions:**
1. Go to your repo → **Settings** → **Actions** → **General**
2. Under "Workflow permissions", select **Read and write permissions**
3. Click **Save**

**Run it manually first:**
1. Go to your repo → **Actions** tab
2. Click **"Generate Snake Contribution Graph"**
3. Click **"Run workflow"** → **Run workflow**

After ~1 minute, an `output` branch will be created with the SVG files. The snake will now animate in your README.

---

## Step 4 — Replacements Required

Search and replace these placeholders in `README.md`:

| Placeholder | Replace With |
|:---|:---|
| `rijulnambiar` | Your actual GitHub username |
| `YOUR_LEETCODE_USERNAME` | Your LeetCode handle |
| `https://your-portfolio-link.com` | Your actual portfolio URL |

---

## Step 5 — Add Repository Links

For each project card in the README, update the GitHub repo badge links:

```
https://github.com/rijulnambiar/edge-ai-accident-detection
https://github.com/rijulnambiar/smart-gait-analysis
https://github.com/rijulnambiar/power-theft-detection
```

Create the repos on GitHub and update the links accordingly.

---

## Optional Enhancements

- **Custom domain portfolio**: Use Vercel or Netlify to deploy a free portfolio site
- **Pin repositories**: On your profile page, pin your 6 best repositories using "Customize your pins"
- **Profile picture**: Upload a professional headshot for maximum recruiter impact

---

*Your profile is now live at: https://github.com/rijulnambiar*
