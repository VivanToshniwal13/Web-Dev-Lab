# P2 — Portfolio repo with an initial commit
**Aim:** Initialize Git and publish a first portfolio commit.

```bash
mkdir portfolio && cd portfolio
git init
echo "# My Portfolio" > README.md
echo "<h1>Hello, I am a web developer</h1>" > index.html
git add .
git status
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```
Replace the remote URL with your own repository.
**Result:** The first commit is pushed to GitHub.
