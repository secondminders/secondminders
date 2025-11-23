# 🤝 Contributing to Secondminders
### An open guide for participating in the movement

Secondminders is a collective, open, ownerless movement.  
There are no founders, no hierarchy, no gatekeepers.  
Everyone is invited to contribute, improve, expand, clarify, and co-create.

This document explains how — philosophically and technically.

---

# 🌱 Principles of Contribution

## **1. The movement is open-source by nature**
All ideas, improvements, expansions, and discussions are welcome.

## **2. Contributions do not require permission**
You don’t need to ask before suggesting improvements.  
Begin wherever you feel inspired.

## **3. No personal ownership**
Ideas belong to the collective.  
Contributions are anonymous in spirit, even if GitHub shows your username.

## **4. Respect the purpose**
The goal of Secondminders is clarity, depth, and collaboration —  
not ideology and not self-promotion.

## **5. Everything can evolve**
Nothing is final.  
All documents — including the principles and manifesto — may be refined by the community.

---

# 🧠 What You Can Contribute

- philosophical extensions
- clarifications
- alternative formulations
- diagrams and conceptual models
- examples of combinatorial intelligence
- research references
- new principles (proposed, not binding)
- edits for clarity or structure
- translations
- discussions in issues
- new documents in the `docs/` folder
- ideas for improving the movement

If your contribution improves collective understanding — it is welcome.

---

# 🌿 Technical Contribution Model
### How to contribute using Git, branches, and pull requests

Secondminders uses a clean, modern, and scalable branch structure.

---

# 🌳 Branch Structure

### 🔵 `main` — Stable Release Branch
- Contains finalized and approved work.
- Protected: no force pushes, no direct commits.
- Only Pull Requests may merge into `main`.
- Linear history enforced (only squash or rebase merges).

### 🟣 `dev` — Development Branch
- Used for ongoing work and integration.
- Not protected — history may be rewritten if needed.
- Feature branches are usually created from `dev`.

### 🟩 `feature/*` — Feature & Task Branches
Every contribution should be made in a dedicated feature branch.

Naming convention:
feature/<short-descriptive-name>

Examples:
feature/social-spaces
feature/whitepaper-outline
feature/update-readme


Do **not** commit directly to `main`.  
Work → `feature/*` → Pull Request → `main` (or `dev` for larger tasks).

---

# 🔁 Workflow: Step-by-Step

## **1. Switch to `dev` and update**
```bash
git checkout dev
git pull
```

## **2. Create a feature branch**
```bash
git checkout -b feature/my-change
```

## **3. Make changes and stage them**
```bash
git add .
```

## **4. Commit your work**
```bash
git commit -m "Describe your change"
```

## **5. Push your branch**
```bash
git push -u origin feature/my-change
```

## **6. Open a Pull Request**
- Target main for small, clean updates
- Target dev for larger or ongoing work

Use “Squash and Merge” or “Rebase and Merge”.
Merge commits are not allowed.

## **7. After merge**
Delete your feature branch:
```bash
git branch -d feature/my-change
git push origin --delete feature/my-change
```
GitHub usually deletes it automatically.

---

# 🧹 Commit Style Guidelines
- Write clear, precise messages:
  - Add multidimensional thinking section
  - Improve prompt fusion chapter
  - Fix typos in manifesto
- Keep commits small and meaningful.
- Avoid unrelated changes in the same commit.
- Use squash merge for a clean, linear history.


```Markdown
docs/
    core-concepts.md
    social-spaces.md
    combinatorial-intelligence.md
    multidimensional-thinking.md
    ...
    diagrams/
MANIFESTO.md
PRINCIPLES.md
CONTRIBUTING.md
LICENSE
README.md
```

# 📄 How to Contribute (Non-technical)

## Option A — GitHub Web Editor
1. Click **“Add file → Create new file”** or **“Edit this file”**.
2. Make your changes.
3. Write a short commit message.
4. Click **“Propose changes”**.
5. Submit a pull request.

## Option B — Fork and Pull Request
1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a pull request.

## Option C — Open an Issue
If you want to discuss an idea before writing it, open an **Issue**.  
Ideas grow through dialogue.

---

# 🌐 Style Guidelines

- Use clear, accessible language.
- Prefer precision over abstraction.
- Avoid personal tone or self-credit.
- Treat ideas as shared and open.
- Keep the spirit of the movement: **collaborative, positive, expansive**.

---

# 🔒 Licensing

All contributions are published under:

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](LICENSE)

**Creative Commons Attribution–ShareAlike 4.0 International  
(CC BY-SA 4.0)**

See the full license text here:  
**[LICENSE](LICENSE)**

By contributing, you agree that your work becomes part of the collective body of the movement  
and may be freely shared and adapted under the same license.

---

# 🌞 Thank You

By contributing, you become part of the combinatorial intelligence that defines Secondminders.  
Together, we create the second mind.

**Welcome.**
