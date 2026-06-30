


Course link-> https://www.geeksforgeeks.org/blogs/ultimate-guide-git-github/
## 1.  Major things to know


Great question! Let me break it all down simply.

---

## What is Git? 🗂️

Git is a **time machine for your code.** It saves snapshots of your project so you can:

- Go back to any previous version
- See what changed and when
- Work on new features without breaking the main site

---

## What is GitHub? ☁️

GitHub is just **Google Drive for your Git project.** It stores your code online so:

- It's backed up
- Others can see/contribute
- You can deploy it live

---

## Core Concepts

### 📸 Commit

A **snapshot** of your project at a point in time. Like a save point in a game.

```bash
git commit -m "added navbar"
```

Every commit has a message describing what changed.

---

### 🌿 Branch

A **parallel version** of your project. Think of it like this:

```
master ──●──●──●──●  (your live website)
              │
feature ──────●──●   (testing new design)
```

- `master` = your main/live code
- You create a new branch to **safely test** new things
- If it works → merge it back to master
- If it breaks → just delete the branch, master is untouched ✅

---

### 🔀 Merge

Combining a branch back into master:

```bash
git merge feature-branch
```

---

### 📤 Push & 📥 Pull

- **Push** = upload your commits to GitHub
- **Pull** = download latest changes from GitHub

```bash
git push   # upload
git pull   # download
```

---

### 🍴 Fork

A **copy of someone else's repo** into your account. You can edit it freely without affecting the original.

---

### 📬 Pull Request (PR)

When you want to **merge your branch into master**, you open a Pull Request on GitHub. Others can review your code before it merges. Used mostly in team projects.

---

## Your Situation — Why 2 Branches?

When you ran `git init`, Git created a `master` branch locally. But GitHub's default is `main`. So now you have:

- `master` → your actual files ✅
- `main` → empty (just README) ❌

**Fix it once and for all:**

```bash
git branch -m master main
git push -u origin main
git push origin --delete master
```

This renames your branch to `main` everywhere and deletes the old `master`. Then set default branch to `main` on GitHub. ✅

---

## Summary Cheatsheet

|Command|What it does|
|---|---|
|`git init`|Start a git project|
|`git add .`|Stage all changes|
|`git commit -m "msg"`|Save a snapshot|
|`git push`|Upload to GitHub|
|`git pull`|Download from GitHub|
|`git branch`|See all branches|
|`git checkout -b name`|Create a new branch|
|`git merge name`|Merge a branch|
|`git log`|See all past commits|
|`git status`|See what changed|

For a solo project like yours, you'll mostly only ever use `add`, `commit`, and `push`! 😊



#### All sequenced steps

When you want to start a completely new project and upload it to a brand-new GitHub repository, this is the exact workflow:

#### Step 1: Create the Repo on GitHub

1. Go to GitHub and click **New** to create a repository.
    
2. Give it a name, but **leave "Initialize this repository with a README" UNCHECKED**. (Keeping it completely empty is easier when linking a local project).
    
3. Click **Create repository**.
    

#### Step 2: Run the Commands in VS Code

GitHub will actually show you a page with the exact commands you need to copy and paste. They look like this:
##### Initialize the local folder as a Git repository
`git init`

##### Add all your current VS Code files to be tracked
`git add .`

##### Save your snapshot
`git commit -m "Initial commit"`

##### Rename your default branch to main (highly recommended standard)
`git branch -M main`

##### Link your local folder to the new GitHub repo
`git remote add origin <YOUR_NEW_REPO_URL>`

##### Push your code up to GitHub
`git push -u origin main`


#### Future Updates

For any future changes or new files you create in that project, you only ever need to run these 3 simple commands:

`git add .`
`git commit -m "your update message"`
`git push`



#### When working in a sub-folder, to change all files in the repository : 

`git add -A`
`git commit -m "your message"`
`git push`

#### Checked folder linked github repository :

`git remote -v`