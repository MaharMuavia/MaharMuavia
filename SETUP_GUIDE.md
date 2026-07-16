# 🚀 Complete Professional GitHub Setup Guide

A full checklist to turn **github.com/MaharMuavia** into a standout, professional profile.

---

## ✅ STEP 1 — Create your profile README repo (most important)

A profile README only appears if it lives in a repo named **exactly** like your username.

1. Go to **https://github.com/new**
2. Repository name: **`MaharMuavia`** (must match your username, case-sensitive)
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**
6. You'll see a *"✨ You found a secret!"* banner — that confirms it's the special profile repo.

Then upload these files into that repo:
```
README.md
.github/workflows/snake.yml
.github/workflows/metrics.yml
```

---

## ✅ STEP 2 — Push the files (using Git)

From this folder, run:

```bash
git init
git add README.md .github
git commit -m "Add professional profile README and automations"
git branch -M main
git remote add origin https://github.com/MaharMuavia/MaharMuavia.git
git push -u origin main
```

> If the repo already has a README, run `git pull origin main --allow-unrelated-histories` first.

---

## ✅ STEP 3 — Enable the Contribution Snake 🐍

1. Push the code (Step 2). This adds `.github/workflows/snake.yml`.
2. Go to your repo → **Actions** tab → enable workflows if prompted.
3. Open **"Generate Contribution Snake"** → click **Run workflow**.
4. It creates an `output` branch with the animated snake SVG.
5. The README already points to it — it will appear within a minute.

---

## ✅ STEP 4 — (Optional) Enable the Metrics image

The `metrics.yml` needs a personal access token:

1. Go to **Settings → Developer settings → Personal access tokens → Tokens (classic)**
2. Generate a token with **`repo`** + **`read:user`** scopes. Name it `METRICS_TOKEN`.
3. In your `MaharMuavia` repo → **Settings → Secrets and variables → Actions → New repository secret**
4. Name: `METRICS_TOKEN`, value: the token you generated.
5. Run the **"Generate Metrics"** workflow from the Actions tab.
6. Add this line wherever you want it in `README.md`:
   ```html
   <img src="github-metrics.svg" alt="Metrics" width="100%"/>
   ```

---

## ✅ STEP 5 — Polish your GitHub account settings

Go to **Settings → Public profile** and fill in:

- [ ] **Profile picture** — a clean, professional headshot or logo
- [ ] **Name** — Muhammad Muavia
- [ ] **Bio** — `Founder @ InventaCore | Full-Stack & AI Developer`
- [ ] **Company** — `@InventaCore`
- [ ] **Location** — your city
- [ ] **Website** — `https://muhammadmuavia.me`
- [ ] **Social links** — add LinkedIn + InventaCore
- [ ] Enable **"Show Achievements on my profile"**
- [ ] Set a custom **profile README pin order**

---

## ✅ STEP 6 — Pin your best repositories

1. On your profile, click **"Customize your pins"**.
2. Pin **4–6 of your strongest projects**.
3. For each pinned repo, make sure it has:
   - [ ] A clear **description**
   - [ ] **Topics/tags** (e.g. `react`, `nextjs`, `ai`)
   - [ ] A good **README** with screenshots + live demo link
   - [ ] A **license** (MIT is common)

Then update the **Featured Projects** section of your README — replace
`REPO_NAME_1` and `REPO_NAME_2` with the real repo names.

---

## 🏆 STEP 7 — Earn GitHub Achievement badges

These are *earned*, not added. Quick wins:

| Badge | How to unlock |
|-------|---------------|
| **Pull Shark** | Get 2 pull requests merged |
| **YOLO** | Merge a PR without review (your own repo counts) |
| **Quickdraw** | Close an issue/PR within 5 minutes of opening |
| **Pair Extraordinaire** | Add a `Co-authored-by:` line to a commit |
| **Starstruck** | Reach 16+ stars on one repo |
| **Galaxy Brain** | Get an accepted answer in GitHub Discussions |

---

## 🎨 Customization tips

- **Change theme colors** — every stats/streak card has a `theme=` parameter.
  Try: `radical`, `dracula`, `github_dark`, `gruvbox`, `tokyonight`, `nord`.
- **Edit the typing animation** — change the `lines=` text in the typing SVG URL.
- **Update your tech stack** — remove badges you don't use, add ones you do.

---

### 📋 Final checklist

- [ ] Profile repo `MaharMuavia` created and public
- [ ] README pushed and rendering
- [ ] Snake workflow ran successfully
- [ ] Profile settings completed (bio, company, links, picture)
- [ ] 4–6 repos pinned with good READMEs
- [ ] Achievements enabled
- [ ] Tech stack reflects your real skills

Once done, your profile will look clean, active, and professional. 🎯
