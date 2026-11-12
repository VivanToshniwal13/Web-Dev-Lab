# P4 — GitHub README and version tags
**Aim:** Document the project and create a release tag.

Write a README with project description, features, setup, usage and author. Then:

```bash
git add README.md
git commit -m "Document portfolio project"
git tag -a v1.0.0 -m "First portfolio release"
git push origin main
git push origin v1.0.0
git tag
```
**Result:** GitHub displays the project documentation and the repository has tag `v1.0.0`.
