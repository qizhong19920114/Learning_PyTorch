# PyTorch-Learning-Path
Repo to document my PyTorch Learning


IMPORTANT: Make sure to use `git remote set-url origin https://<personal_token>@github.com/qizhong19920114/PyTorch-Learning-Path.git` if i first clone this. Then use `git pull origin main`


Common Problem: 
- Q:"fatal: Authentication failed for" when git push
- A: if i first clone this. I need ot run `git pull origin main`. Then when Git push, I need to run `git remote set-url origin https://<personal_token>@github.com/qizhong19920114/PyTorch-Learning-Path.git` before git push.  The <personal_token> here needs to be generated every 30 days from Setting > Developer settings > Personal access token > Tokens (classic)

- an altertive is to add token when you clone the repo. E.g: git clone https://qizhong19920114:<personal_token>@github.com/qizhong19920114/streamlit_ml_app.git


- Q: How to fix "modified content, untracked content" in git?
- A: Remove .git from subfolders
