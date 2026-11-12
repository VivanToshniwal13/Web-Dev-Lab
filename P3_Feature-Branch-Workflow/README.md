# P3 — Feature-branch Git workflow
**Aim:** Develop a feature on a separate branch and merge it safely.

```bash
git switch main
git pull origin main
git switch -c feature/about-section
# Add an About section to index.html
git add index.html
git commit -m "Add about section"
git push -u origin feature/about-section
```
On GitHub, open a pull request from `feature/about-section` into `main`, review and merge it. Then:

```bash
git switch main
git pull origin main
git branch -d feature/about-section
```
**Result:** The feature is merged through a pull request.
