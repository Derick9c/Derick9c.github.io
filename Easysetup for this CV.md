## Easy Setup for GitHub CV

This file outlines a step-by-step workflow to set up a GitHub Pages CV.

### Step 1: Create Repository

* Create a repository with the same name as your GitHub username, e.g., `Derick9c.github.io`.
* Initialize with a `README.md` file.

### Step 2: Write Markdown CV

* Create a file named `README.md` in the root directory.
* Use Markdown syntax to write your full CV content.

Example:

```markdown
# Derick (Wu Zhangchi)
Computational Social Science & Smart Governance

## Education
- M.S., Computational Social Science — CUHK, Shenzhen — 2024.09–2025.06
- B.A., International Economics and Trade — Nanjing Normal University — 2020.09–2024.06
```

### Step 3: Create `_config.yml`

* Create `_config.yml` in the root directory.
* Use a template or borrow configuration from other CV repositories.

Example:

```yml
title: Wu Zhangchi
logo: assets/img/profile.jpg
description: My CV — Computational Social Science & Smart Governance
show_downloads: false
theme: jekyll-theme-minimal

```

### Step 4: Upload Images

* Create a folder `assets/img/`.
* Upload your profile picture or other images to this folder.
* Ensure file names match exactly with `_config.yml` and Markdown references.

### Step 5: Reference Images in CV

* In Markdown:

```markdown
![Profile](assets/img/profile.jpg)
```



### Step 6: Commit and Deploy

1. Commit all files (`README.md` / `index.md` / `_config.yml` / `assets/img/...`).
2. Push to GitHub.
3. Enable GitHub Pages in repository settings (`Settings → Pages → main branch`).
4. Wait a few minutes and access your CV at `https://USERNAME.github.io`.

### Step 7: Debug Paths

* If images do not load, check file name case and relative paths.
* If logo does not display, check if the theme supports logo and path in `_config.yml`.
* Refresh browser cache if needed.

* notice: I used the jekyll-theme-minimal(it's github offical theme),you can get more information about the github style:https://docs.github.com/en/pages.
