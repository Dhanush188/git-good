# Dummy Merge Conflict Repo

Purpose: Demonstrate a merge conflict by editing the same lines in two branches.

Instructions (from feature-b):
1. **Start on main:** Ensure you're on `main` and up to date.
2. **Merge feature-b first:** `git checkout main && git merge feature-b`
3. **Then merge feature-a:** `git merge feature-a`
4. You should see a merge conflict in README.md because both branches modify the same lines differently.

Conflicting section (feature-b version):
- Line A: This is the FEATURE-B version of the conflict line.
- Line B: Edited by FEATURE-B to force a conflict.
