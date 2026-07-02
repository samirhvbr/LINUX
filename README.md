# LINUX

## 🔄 Before you start: `git pull`

**ALWAYS** check for remote updates before writing or changing anything in this repository:

```bash
git pull          # already pre-authorized (allow)
```

Working on top of an outdated base causes conflicts. Pull first, always. To just inspect beforehand: `git fetch && git status`.

## Critical points

- **Version:** `version.md` is the version of our work (currently `0.0.2`); `__version__=1.2.15` (in `shvterm/__init__.py`) is the upstream fork baseline — frozen to track merges. Details in [AGENTS.md](AGENTS.md).
- **Commits (MANDATORY, always):** format `version - comment` (e.g., `0.0.3 - Adiciona flag --json ao comando host list`). The version comes from `version.md`; do the bump **in the same commit** as the change. Message **in Portuguese**, descriptive enough for future searching. Never use the frozen `1.2.x` lineage. Details in [AGENTS.md](AGENTS.md#34-formato-do-commit).
