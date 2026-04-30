# 1. Add the original repo as "upstream" (one-time setup)
git remote add upstream https://github.com/original-owner/original-repo.git

# 2. Verify remotes are set correctly
git remote -v

# 3. Fetch latest changes from upstream
git fetch upstream

# 4. Switch to your local main branch
git checkout main

# 5. Merge upstream's main into your local main
git merge upstream/main

# 6. Push the updated main to your fork on GitHub
git push origin main