# How to publish this to GitHub

Two ways. Pick whichever you prefer.

---

## Option A — hand it to Claude Code (easiest)

Download the `chris-skill` folder, then open Claude Code in the folder that
*contains* it and paste this:

> Take the `chris-skill` folder in this directory, initialize it as a git repo,
> and publish it to GitHub as a new public repository under my account
> `chrisdaixinhui`, named `chris-skill`. Use the description:
> "A person, distilled into a Skill. How I think, decide, and write."
> Set up the remote, make the initial commit, and push to `main`.

Claude Code has `gh` (the GitHub CLI) available and will handle auth, repo
creation, and the push. If it asks you to authenticate, run `gh auth login`
once and it'll take over from there.

---

## Option B — do it yourself in the terminal

From inside the `chris-skill` folder:

```bash
# one-time, if you've never used gh
gh auth login

git init
git add .
git commit -m "chris.skill — a person, distilled"
git branch -M main

# creates the repo and pushes in one step
gh repo create chris-skill \
  --public \
  --source=. \
  --description "A person, distilled into a Skill. How I think, decide, and write." \
  --push
```

If you'd rather not use `gh`: create an empty repo named `chris-skill` on
github.com first (no README, no license — this folder already has both), then:

```bash
git init
git add .
git commit -m "chris.skill — a person, distilled"
git branch -M main
git remote add origin https://github.com/chrisdaixinhui/chris-skill.git
git push -u origin main
```

---

## Before you push — a checklist

- [ ] **Read `references/mind.md` one more time.** It's the most personal file
      in the repo. Everything in it is either something you said or a pattern
      derived from it, and people are described as situations rather than
      names — but you should be the one who decides it's okay to be public.
- [ ] **Same for `references/writing_samples/`.** `business_analysis.md`
      discusses a real employer and a real colleague's working conditions.
      Consider whether you want that public, or whether it should move to a
      private folder (`.gitignore` already excludes `private/`).
- [ ] Decide whether the repo should be **public or private**. `gh repo create`
      takes `--private` instead of `--public` if you'd rather keep it between
      you and whoever you send the link to.
- [ ] Optionally add repo topics on GitHub for discoverability:
      `claude-skill`, `agent-skills`, `persona`, `writing`.

---

## After it's up

The install line in the README will already work:

```bash
git clone https://github.com/chrisdaixinhui/chris-skill ~/.claude/skills/chris
```

Then `/chris` in Claude Code, or ask any agent for something "in Chris's voice."
