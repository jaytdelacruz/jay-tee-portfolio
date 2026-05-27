# 📋 Guide for Tomorrow — New Computer Setup

## Before Anything Else

Open a terminal (Command Prompt or PowerShell) and do these steps in order.

---

## Step 1 — Check if Git is installed

```
git --version
```

✅ If you see a version number (e.g. `git version 2.x.x`) → go to Step 2  
❌ If you get an error → download and install Git first: https://git-scm.com/download/win  
*(Just click Next through the installer, default settings are fine)*

---

## Step 2 — Set up your Git identity (first time only)

```
git config --global user.name "Jay Tee Dela Cruz"
git config --global user.email "delajayt@gmail.com"
```

---

## Step 3 — Clone the portfolio repo

```
git clone https://github.com/jaytdelacruz/jay-tee-portfolio.git
```

This downloads your portfolio files to your computer.

---

## Step 4 — Go into the folder

```
cd jay-tee-portfolio
```

---

## Step 5 — Open Claude Code

Open Claude Code and point it to the `jay-tee-portfolio` folder you just cloned.

---

## ✅ You're ready!

---

## Every Time You Work (Daily Workflow)

### Before editing — always pull first:
```
git pull
```

### After making changes — save and push:
```
git add index.html
git commit -m "describe what you changed"
git push
```

### Then wait ~30 seconds → your live site updates automatically:
🌐 https://jay-tee-portfolio.vercel.app/

---

## Important Links

| What | Link |
|---|---|
| Live site | https://jay-tee-portfolio.vercel.app/ |
| GitHub repo | https://github.com/jaytdelacruz/jay-tee-portfolio |
| Betty's site | https://bettys-restaurant.vercel.app/ |

---

## Files in This Project

| File | What it is |
|---|---|
| `index.html` | The entire portfolio website |
| `profile.png` | Your profile photo |
| `resume.pdf` | *(Add this when ready — CV download button is already set up)* |
| `smm-*.jpg` | Social media work images |
| `cert-*.pdf` | UX+ Conference certificates |
| `case-study-01-bettys.md` | Betty's website case study notes |
| `case-study-04-ai-smm-generator.md` | AI SMM Generator case study notes |

---

## Things Still To Do

- [ ] Upload `resume.pdf` to the folder and push (Download CV button is already live)
- [ ] Add proof/screenshot to Case Study 04 (AI SMM Generator) when it's ready
- [ ] Add Case Study 05 for Betty's social media content
