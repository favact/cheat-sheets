# GitHub

GitHub is an Internet hosting service for software development and version control using Git ([[git]]), plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

---
## GitHub Actions

Automate, customize, and execute your software development workflows right in your repository with GitHub Actions ([[github-actions]]). You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.

## Create a new repository on the command line

```git
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/favact/test.git
git push -u origin main
```

## Push an existing repository from the command line

```git
git remote add origin https://github.com/favact/test.git
git branch -M main
git push -u origin main
```