# Git-cmd-for-beginners-to-Advanced
Git access for the beginner to Advanced
<!-- README.md -->

<style>
.wrapper {
  background: linear-gradient(135deg, #ffccbc, #ffe0b2, #f8bbd0, #d1c4e9);
  padding: 2rem;
  border-radius: 12px;
}
</style>

<div class="wrapper">

# 🐙 Git Commands Reference

<p>
  <img src="https://avatars.githubusercontent.com/u/91134716?v=4" alt="Profile Photo" width="120" style="border-radius:50%; box-shadow:0 0 15px rgba(0,0,0,0.3);"/>
</p>

<p>
  <strong style="margin-right:1rem;">🏷️ Verify Now Post</strong>
  <strong>🔔 Notify New Post</strong>
</p>

<p>
  <a href="https://devopsenginer.in" style="margin:0 .5rem;">🌐 devopsenginer.in</a>
  <a href="https://github.com/WizardBrew" style="margin:0 .5rem;">🐙 GitHub</a>
  <a href="https://www.linkedin.com/in/parvezmustak8004/" style="margin:0 .5rem;">💼 LinkedIn</a>
  <a href="mailto:wizardbrew@outlook.com" style="margin:0 .5rem;">✉️ Email</a>
</p>

---

## 🔰 Beginners

| Command     | Description                         | Example                                |
|-------------|-------------------------------------|----------------------------------------|
| `git init`  | Initializes a new Git repository    | `git init my-project`                  |
| `git clone` | Copies an existing repository       | `git clone https://github.com/user/repo.git` |
| `git add`   | Stages changes for the next commit  | `git add file.txt`                     |
| `git commit`| Records staged changes              | `git commit -m "Initial commit"`       |
| `git status`| Displays working directory status   | `git status`                           |
| `git push`  | Sends local commits to remote       | `git push origin main`                 |

---

## ⚙️ Intermediate

| Command         | Description                               | Example                                  |
|-----------------|-------------------------------------------|------------------------------------------|
| `git branch`    | Lists, creates, or deletes branches       | `git branch feature-login`               |
| `git checkout`  | Switches branches or restores working tree| `git checkout feature-login`             |
| `git merge`     | Integrates changes from another branch    | `git merge feature-login`                |
| `git log`       | Shows commit history                      | `git log --oneline`                      |
| `git stash`     | Temporarily shelves uncommitted changes   | `git stash save "WIP: login feature"`    |
| `git tag`       | Creates, lists, or deletes tags           | `git tag v1.0.0`                         |

---

## 🚀 Advanced

| Command              | Description                                            | Example                                                        |
|----------------------|--------------------------------------------------------|----------------------------------------------------------------|
| `git rebase`         | Reapplies commits on top of another base tip           | `git checkout feature && git rebase main`                      |
| `git cherry-pick`    | Applies a specific commit from another branch          | `git cherry-pick a1b2c3d4`                                     |
| `git bisect`         | Uses binary search to find the commit that broke code  | `git bisect start; git bisect bad; git bisect good v1.0`       |
| `git reflog`         | Records updates to local references                    | `git reflog`                                                   |
| `git submodule`      | Manages nested repositories within a parent project    | `git submodule add https://github.com/user/lib.git libs/lib`   |
| `git filter-branch`  | Rewrites branches by filtering commit history          | `git filter-branch --tree-filter 'rm -f secrets.txt' HEAD`     |

---

*This README is wrapped in a colorful gradient container to match the WizardBrew™ theme.*  
</div>
