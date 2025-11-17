# Portfolio — Rehan Haider

This folder contains the static portfolio site for Rehan Haider.

Contents:
- `portfolio.html` — main site
- `assets/` — images and PDF resume

What I did for you here:
- Prepared the site and embedded the updated resume PDF `assets/Rehan_Haider_Resume_Updated.pdf`.
- Added this README and a `.gitignore`.

How to push to GitHub (choose one):

1) Create a new empty repository on GitHub (via the website) and then run these commands from this folder:

```powershell
# run from: c:\university work\web lab\phase1
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

2) Or, if you use the GitHub CLI (gh) and are logged in:

```powershell
# create repo and push in one line (changes remote automatically)
gh repo create YOUR_USERNAME/YOUR_REPO_NAME --public --source=. --remote=origin --push
```

Notes:
- Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and desired repo name.
- If your repo is private, omit `--public` and/or set appropriate visibility.
- If your git credential helper is not configured, pushing will prompt you for credentials or your PAT.

If you want, I can (a) create a backup of the previous resume file, and (b) attempt to create the remote repo for you using the gh CLI if you confirm you have it installed and are logged in. Otherwise, run the commands above to publish the project.
