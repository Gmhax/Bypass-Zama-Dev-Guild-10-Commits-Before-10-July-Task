# Bypass-Zama-Dev-Guild-10-Commits-Before-10-July-Task

## Instructions
1. Create a New Repository
- Go to: https://github.com/new
- Repository Name: 20commits
- Tick "Add a README file"
- Click Create repository

<img width="1286" height="421" alt="image" src="https://github.com/user-attachments/assets/cf986f1e-ce2c-4bb8-887c-c5b84d3696f8" />
- Click Code then Create Codespace

2. Clone your GitHub repo
```
cd ~
git clone https://github.com/your-username/your-repo.git
cd 20commits
```

3. Authenticate Git
```
git config --global user.name "YourGitHubUsername"
git config --global user.email "YourEmail@example.com"
```

4. Make Your Commits
```
echo "Commit 1 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:00:01" GIT_COMMITTER_DATE="2025-06-30T01:00:01" git commit -m "Commit 1"

echo "Commit 2 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:15:13" GIT_COMMITTER_DATE="2025-06-30T01:15:13" git commit -m "Commit 2"
```
# ... repeat up to Commit 20

5. Push Your Commits to GitHub
```
git push
git log --oneline
```


## DONE MA BROO!!






