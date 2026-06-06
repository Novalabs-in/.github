# Contributing to Novalabs-in 🌌

First off, thank you for taking the time to contribute! We are a builder-first community, and we appreciate all contributions, whether it's fixing a bug, upgrading documentation, or implementing a major new feature.

Following these guidelines helps us process contributions quickly and efficiently.

---

## 📜 Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please report any violations or inappropriate behavior to `security@novalabs.in`.

---

## ⚡ How Can I Contribute?

### 🔎 Finding an Issue
We label issues that are suitable for contributors:
- **`good first issue`**: Simple issues that are perfect for getting started with the repository.
- **`help wanted`**: General tasks where we would love community help.

If you want to suggest a new feature or report a bug, please create a new issue using our interactive issue templates before writing code.

### 🛠️ Local Development Setup
1. **Fork** the repository you want to work on.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/repository-name.git
   cd repository-name
   ```
3. Set up the upstream remote to keep your fork in sync:
   ```bash
   git remote add upstream https://github.com/Novalabs-in/repository-name.git
   ```
4. Install dependencies:
   - For **Python** projects: Setup virtual environment (`python3 -m venv .venv && source .venv/bin/activate`) and run `pip install -r requirements.txt`.
   - For **Node.js/TypeScript** projects: Run `npm install` or `yarn install`.
   - For **Go** projects: Run `go mod download`.

---

## 🌿 Branching Strategy
Create a feature branch from the default branch (usually `main`):
```bash
git checkout -b feat/your-feature-name
# or fix/bug-description
```

We recommend using the following branch naming prefixes:
- `feat/` — for new features
- `fix/` — for bug fixes
- `docs/` — for documentation updates
- `refactor/` — for code restructuring without feature changes
- `test/` — for adding or updating tests
- `perf/` — for performance improvements
- `ci/` — for CI/CD changes

---

## 💬 Commit Message Guidelines
We follow the **Conventional Commits** specification for all commit messages. This helps us auto-generate beautiful changelogs and maintain clean git histories.

Format: `<type>(<scope>): <description>`

Examples:
- `feat(auth): add JWT signature validation middleware`
- `fix(excel): resolve memory leak when loading large workbooks`
- `docs(readme): add setup and installation instructions`
- `refactor(db): optimize postgres connection pool size`
- `test(api): add unit tests for health check endpoint`

---

## 🧪 Coding & Quality Standards
- **Keep it simple**: Write clean, readable, and self-documenting code.
- **Linting & Formatting**: Ensure your code passes all lint and formatting checks.
  - Python: We use `black` and `flake8` for formatting and linting.
  - JavaScript/TypeScript: We use `eslint` and `prettier`.
- **Tests**: Write unit tests for any new features or bug fixes. Run the existing test suite locally and ensure everything passes.

---

## 🚀 Submitting a Pull Request
1. Keep your fork synced with the upstream `main` branch:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   git checkout your-feature-branch
   git rebase main
   ```
2. **Push** your branch to your GitHub fork:
   ```bash
   git push origin your-feature-branch
   ```
3. Open a **Pull Request** against the upstream `main` branch.
4. Fill out the provided **Pull Request Template** completely.
5. Link any related issues in the PR description (e.g. `Closes #123`).
6. A maintainer will review your code shortly. Address any feedback and keep committing to the same branch; the PR will update automatically.

---

Thank you for building the future of open-source with Novalabs-in! 🚀
