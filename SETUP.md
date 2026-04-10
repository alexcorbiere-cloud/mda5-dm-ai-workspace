# Setup Guide

**Time required:** ~30 minutes  
**Skill level:** Beginner-friendly

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to https://github.com
2. Click "Sign up"
3. Use your personal email (alex.corbiere@gmail.com or pm.me)
4. Choose a username (e.g., `alex-corbiere` or similar)
5. Verify your email

---

## Step 2: Create the Repository

1. Click the **+** in the top right → **New repository**
2. Repository name: `mda5-dm-ai-workspace`
3. Description: `Shared AI workspace for medical/legal coordination`
4. **Private** (important — this contains medical info)
5. Check "Add a README file" (we'll replace it)
6. Click **Create repository**

---

## Step 3: Upload the Files

### Option A: Web Upload (Easiest)

1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop the entire folder contents from the zip
3. Or click "choose your files" and select them
4. Commit message: "Initial setup"
5. Click **Commit changes**

### Option B: GitHub Desktop (More Robust)

1. Download GitHub Desktop: https://desktop.github.com
2. Sign in with your GitHub account
3. Clone your new repo to your computer
4. Copy the files from the zip into the cloned folder
5. In GitHub Desktop, add a commit message and click **Commit to main**
6. Click **Push origin**

---

## Step 4: Note Your Raw URLs

Once uploaded, your files are accessible at:

```
https://raw.githubusercontent.com/YOUR-USERNAME/mda5-dm-ai-workspace/main/HANDOVER.md
https://raw.githubusercontent.com/YOUR-USERNAME/mda5-dm-ai-workspace/main/TIMELINE.md
```

Replace `YOUR-USERNAME` with your actual GitHub username.

---

## Step 5: Test with Claude

Start a new Claude conversation and say:

> "Fetch and read: https://raw.githubusercontent.com/YOUR-USERNAME/mda5-dm-ai-workspace/main/HANDOVER.md"

If it works, Claude will summarise the contents.

---

## Step 6: Test with Gemini

Same process. If Gemini has GitHub integration, you may be able to connect the repo directly.

---

## Ongoing Usage

**To edit files:**
1. Go to your repo on GitHub
2. Click the file you want to edit
3. Click the pencil icon (edit)
4. Make changes
5. Commit with a message

**To check AI-proposed edits:**
1. Go to `PENDING/proposed-edits.md`
2. Review proposed changes
3. If approved, manually apply them to the target file
4. Update status in proposed-edits.md

---

## Security Notes

- Repo is **private** — only you can see it
- Don't share the raw URLs publicly
- You can add collaborators if needed (Bernadette, for example)

---

## If Something Breaks

The repo has version history. You can always:
1. Click a file
2. Click "History"
3. View or revert to previous versions

---

*You've got this. It's just clicking buttons.*
