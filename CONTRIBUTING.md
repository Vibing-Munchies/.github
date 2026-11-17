# Contributing

Vibing Munchies is a friends-only org: every member has write access to every repo.

## Ground rules

- Repos are **private**. Nothing goes public without the repo owner's OK — only org owners can change visibility or delete repos.
- `main` is the shipping branch. Small fixes may go straight to `main`; anything bigger goes through a PR so the repo owner sees it.
- Agent-written code is welcome — you still own what you push. Read the diff, run it once.
- Never commit secrets. Use a gitignored `.env` or GitHub Actions secrets.
- Commit messages: short imperative subject; the body explains why.

## Starting a new project

1. `gh repo create Vibing-Munchies/<name> --private --clone`
2. Add a README: what it does, how to run it, which agent/model built it.
3. Add a LICENSE if you ever plan to share it outside the org.
