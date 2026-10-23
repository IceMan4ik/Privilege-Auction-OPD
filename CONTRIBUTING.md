# Contributing

🇷🇺 [Русская версия](CONTRIBUTING.ru.md) | 🇬🇧 English version

---

## 🚀 Getting Started

```bash
# 1. Fork and clone
# Click the "Fork" button on GitHub.com, then open your terminal:
git clone https://github.com/<YOUR-USERNAME>/Privilege-Auction-OPD.git
cd Privilege-Auction-OPD

# 2. Add upstream remote to sync with the main repository
git remote add upstream https://github.com/IceMan4ik/Privilege-Auction-OPD.git

# 3. Setup Environment
# Follow the setup instructions in the main README.md 
# (install dependencies, build the project, etc., based on the chosen tech stack)
```

---

## 🌳 Branching

Always create new branches from the `dev` branch:

```bash
git checkout dev
git pull upstream dev
git checkout -b feature/your-feature-name
```

**Naming Conventions:**
- `feature/short-description` — for new features
- `fix/short-description` — for bug fixes
- `docs/short-description` — for documentation updates

**Rule:** One branch = one specific task.

---

## 📝 Commits

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```text
<type>(<scope>): <description>
```

**Allowed Types:** `feat`, `fix`, `docs`, `refactor`, `test`, `chore`

**Examples:**
```bash
feat(api): add endpoint for user registration
fix(auth): handle missing token gracefully
docs(readme): update installation steps
```

---

## 🔀 Pull Request (PR) Rules

1. **Target Branch:** Always create your PR into the `dev` branch. **NEVER** target `main` directly.
2. **Pre-PR Checklist:** Before opening a PR, ensure that:
   - [ ] Your code runs without errors locally.
   - [ ] You have added tests for new logic (if applicable).
   - [ ] Your branch is up to date with `dev` (resolve any merge conflicts locally).
3. **CI/CD Checks:** GitHub Actions will automatically run checks on your PR. If the checks fail (red cross ❌), the PR will not be reviewed until the issues are fixed.
4. **Description:** Provide a clear, short description of what your PR does. Example: *"Added validation for auction bids and corresponding unit tests"*.
