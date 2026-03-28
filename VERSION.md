# Example
https://githubachievements.com/

# RECOVERY
git log --oneline -n 5

Copy-Item .env $env:TEMP\.env.backup
git reset --hard 80f714fc
git clean -fd
Copy-Item $env:TEMP\.env.backup .env -Force
git push origin master --force
python run.py

# UPDATE
git add .
git commit -m "v0.0.3 - test language links"
git push

# DEV LOG
v0.0.1 - create project files
v0.0.2 - create github pages
v0.0.3 - test language links
