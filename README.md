echo "# 999-updates" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/itsMorgen/999-updates.git
git push -u origin main
