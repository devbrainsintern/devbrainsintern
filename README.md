# 🚀 Welcome to JSDEVBRAINS — Intern Hub

> **Build with confidence. Learn with curiosity. Deliver with excellence.**

Welcome aboard! You are now part of a team building real software for clients across **Malaysia 🇲🇾, Germany 🇩🇪, Singapore 🇸🇬, India 🇮🇳, United Kingdom 🇬🇧, and the Middle East 🌍**.

This isn't a sandbox. Your code matters. Your contributions ship to real users.

---

## 🎯 What You'll Walk Away With

By the end of your internship, you will be able to:

- ✅ Use Git and GitHub confidently in a team environment
- ✅ Create and manage branches, Pull Requests, and code reviews
- ✅ Write clean, maintainable, and well-documented code
- ✅ Understand the full software development lifecycle
- ✅ Work professionally in a collaborative engineering team
- ✅ Solve problems independently — and know when to ask for help

---

## 🧭 The Internship Formula

```
Learn → Practice → Build → Review → Improve → Repeat
```

Every commit you write, every PR you open, every bug you fix — it's real experience. Treat it that way.

---

## 🔀 Git & GitHub Learning Path

### Beginner — Get Oriented

Understand the basics before writing a single line.

| Concept | What It Means |
|---|---|
| Git | Version control — tracks every change you make |
| GitHub | The platform where your team shares and reviews code |
| Repository | A project folder tracked by Git |
| Commit | A saved snapshot of your changes |
| Push / Pull | Sync your work with the team |

**Essential commands:**

```bash
git clone <repository-url>     # Download the repo locally
git status                     # See what's changed
git add .                      # Stage all changes
git commit -m "Your message"   # Save a snapshot
git push origin branch-name    # Upload your changes
git pull origin main           # Get the latest from the team
```

---

### Intermediate — Work Like a Team

```bash
# Always create a branch for your work — never commit directly to main
git checkout -b intern/your-name-task

# Switch back to main
git checkout main

# Merge a branch (after PR review, not manually in most cases)
git merge branch-name
```

Key concepts to master:

- **Branching strategy** — isolated work, clean history
- **Merge conflicts** — how to resolve them calmly
- **Pull Requests** — the heart of team code review
- **Issue tracking** — communicate your progress clearly

---

### Advanced — Level Up

Once you're comfortable, explore:

- `git rebase` — cleaner commit history
- `git cherry-pick` — apply specific commits across branches
- **Git Tags & Releases** — marking stable versions
- **GitHub Actions** — automating tests and deployments
- **CI/CD fundamentals** — code that ships itself

---

## 🧰 GitHub Features — Your Full Toolkit

GitHub is more than just code storage. Every feature listed below is used by professional engineers daily. Learn them, and you'll work like one.

---

### 📋 Issues — Where Work Begins

Every task, bug, or feature starts as an **Issue**.

**How to use Issues:**

1. Go to the **Issues** tab in the repository
2. Click **New Issue**
3. Give it a clear title: `[Bug] Login button not responding on mobile`
4. Describe: what happened, what you expected, steps to reproduce
5. Assign it to yourself (or your supervisor will assign it to you)
6. Add a **Label**: `bug`, `feature`, `documentation`, `enhancement`
7. Add it to a **Milestone** if one exists

**Good issue title examples:**

```
✅ [Feature] Add dark mode toggle to settings page
✅ [Bug] API returns 500 on empty search query
✅ [Docs] Update README with new environment variables

❌ fix bug
❌ update code
❌ stuff
```

**Reference issues in commits:**

```bash
git commit -m "Fix login redirect — closes #42"
```

GitHub will automatically close Issue #42 when this commit merges to `main`.

---

### 🌿 Branches — Your Safe Workspace

Branches let you work without touching anyone else's code.

**Our branch naming convention:**

```bash
intern/your-name-feature-name     # Your work
feature/short-description         # New features
bugfix/what-you-are-fixing        # Bug fixes
hotfix/critical-fix               # Urgent production fixes
release/v1.2.0                    # Release preparation
```

**Branch workflow:**

```bash
# 1. Always start from the latest main
git checkout main
git pull origin main

# 2. Create your branch
git checkout -b intern/ali-user-profile-page

# 3. Do your work, commit often
git add .
git commit -m "Add profile avatar upload component"

# 4. Push your branch
git push origin intern/ali-user-profile-page

# 5. Open a Pull Request on GitHub
```

---

### 🔁 Pull Requests (PRs) — How Code Gets Reviewed

A Pull Request is a formal request to merge your branch into `main`. It's how the team reviews your work before it ships.

**How to write a great PR:**

```markdown
## What this PR does
Adds profile avatar upload functionality with image compression.

## Why
Closes #38 — users were unable to update their profile photo.

## Changes
- Added `AvatarUpload` component
- Integrated with `/api/users/avatar` endpoint
- Added file size validation (max 2MB)
- Added unit tests

## How to test
1. Log in as any user
2. Go to Settings > Profile
3. Click "Change Photo"
4. Upload an image — should compress and preview before saving

## Screenshots
[Attach before/after screenshots here]
```

**PR etiquette:**

- Keep PRs small and focused — one feature or fix per PR
- Don't open a PR for unfinished work (use **Draft PR** instead)
- Respond to review comments promptly
- Never merge your own PR — wait for a reviewer

---

### 🔍 Code Reviews — Learning in Action

Code reviews are not criticism. They are the fastest way to learn.

**As a reviewer:**

```
✅ "Consider extracting this into a helper function for reuse"
✅ "This could throw an error if `user` is null — can we add a guard?"
✅ "Nice approach! One small suggestion..."

❌ "This is wrong"
❌ "Why did you do it this way?"
❌ "This is bad code"
```

**As an author receiving feedback:**

- Read every comment carefully
- Ask for clarification if you don't understand
- Don't take it personally — the reviewer is improving the product
- Respond to every comment, even with just "Fixed ✅"

**Review comment types on GitHub:**

| Type | When to use |
|---|---|
| `Comment` | General observation, no action needed |
| `Suggest change` | You have a specific fix ready |
| `Request changes` | Blocks merge — must be resolved |
| `Approve` | Ready to merge |

---

### 📌 GitHub Projects — Track Your Work

GitHub Projects is a built-in task board (like Trello or Jira) linked directly to your Issues and PRs.

**Board columns used at JSDEVBRAINS:**

```
Backlog → To Do → In Progress → In Review → Done
```

**How to use it:**

1. Open the **Projects** tab
2. Find the project board for your team
3. Move your Issue/PR card as work progresses
4. Update the card status when you push new commits

This lets your team know exactly where you are without asking.

---

### 🏷️ Labels & Milestones — Stay Organized

**Labels** categorize your issues. Standard labels:

| Label | Meaning |
|---|---|
| `bug` | Something is broken |
| `feature` | New functionality |
| `documentation` | Docs update needed |
| `good first issue` | Suitable for interns |
| `help wanted` | Team needs input |
| `priority: high` | Do this first |
| `blocked` | Waiting on something |

**Milestones** group issues by sprint or release:

- `Sprint 1 — June 2025`
- `v1.0.0 Release`
- `Internship Deliverables`

Assign your issues to the correct milestone so everyone tracks progress.

---

### 💬 GitHub Discussions — Ask, Share, Learn

GitHub Discussions is the team knowledge base. Use it instead of DMs for questions that others might benefit from too.

**Good uses for Discussions:**

- "What's the team's preferred way to handle auth errors?"
- "Anyone have experience with this MongoDB aggregation?"
- "Sharing a useful article on React performance"

Post your learnings here. Future interns will thank you.

---

### ⚙️ GitHub Actions — Automation Basics

GitHub Actions runs automated tasks every time you push code.

**What Actions do at JSDEVBRAINS:**

```
You push code →
  ├── Linter checks for formatting issues
  ├── Tests run automatically
  ├── Build is compiled and verified
  └── Deploy preview is generated (staging environment)
```

You don't need to configure Actions as an intern, but you should understand the output. If a red ❌ appears on your PR, check the Actions log to see what failed — and fix it before asking for review.

**Reading an Actions failure:**

1. Click the red ❌ on your PR
2. Click the failed job name
3. Expand the failed step
4. Read the error message — it's almost always descriptive
5. Fix the code, push again

---

### 🔔 Notifications — Stay in the Loop

Configure your GitHub notifications so you never miss a review request or comment.

**Recommended settings:**

- Watch repositories you're actively working on
- Enable email notifications for **PR reviews** and **mentions**
- Check GitHub at least once every morning

---

### 📊 GitHub Insights — See Your Progress

Go to the **Insights** tab on any repository to see:

- **Contributors** — who has committed what
- **Commits** — activity over time
- **Code frequency** — lines added/removed

Your commits are visible. Make them count.

---

## 💻 Tech Stack at JSDEVBRAINS

### Frontend
`HTML5` · `CSS3` · `JavaScript` · `TypeScript` · `React.js` · `Next.js`

### Backend
`Node.js` · `Express.js` · `REST APIs` · `Authentication & Authorization`

### Databases
`MySQL` · `PostgreSQL` · `MongoDB`

### DevOps
`Linux` · `Docker` · `CI/CD` · `Cloud Platforms`

You don't need to master all of this today. Focus on what your current task requires, and build outward from there.

---

## 🔐 Security — Non-Negotiable

**Never commit secrets.** Not once. Not "just for testing."

```bash
# ❌ Never commit these
.env
.env.local
*.pem
*_secret*
```

Add them to `.gitignore` — always.

| What to avoid | What to do instead |
|---|---|
| Hardcoded passwords | Use environment variables |
| API keys in code | Load from `.env` files |
| Production credentials | Ask your supervisor |

One leaked credential can compromise a client's system. Take this seriously.

---

## 🧠 The Engineering Mindset

When you're stuck, work through this before pinging anyone:

1. **Understand the problem** — Can you explain it in plain words?
2. **Read the docs** — Official documentation exists for a reason
3. **Search for solutions** — Stack Overflow, GitHub Issues, ChatGPT
4. **Try something** — A failed attempt teaches you more than waiting
5. **Test it** — Does it actually work? Edge cases?
6. **Ask for help** — With context: what you tried, what happened, what you expected
7. **Document it** — Write down what you learned. Future-you will thank you.

> A great engineer doesn't know everything.
> A great engineer knows **how to find out**.

---

## 📖 Professional Skills Matter Too

Technical ability gets you in the room. These keep you there:

- **Clear communication** — write updates, ask precise questions
- **Ownership** — don't wait to be told; take initiative
- **Time management** — estimate, track, and flag blockers early
- **Documentation** — if it isn't written down, it didn't happen
- **Team collaboration** — your teammates' success is your success

---

## 🏁 Day One Checklist

- [ ] Clone this repository
- [ ] Create your branch: `intern/your-name`
- [ ] Add `.env` to `.gitignore`
- [ ] Read through this README fully
- [ ] Open your first Issue and assign it to yourself
- [ ] Introduce yourself in the team channel
- [ ] Ask your supervisor what your first task is

---

## 🌱 A Note From the Team

You were selected because we believe in your potential. The gap between where you are now and where you want to be isn't talent — it's reps. Every PR, every review comment, every deployment is a rep.

Show up. Stay curious. Don't be afraid to make mistakes — be afraid of making the same one twice.

**We're glad you're here. Now let's build something.**

---

*JSDEVBRAINS Digital Private Limited — Internal Use*
