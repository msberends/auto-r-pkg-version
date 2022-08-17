# test

## Set up Git prehook for automated semantic versioning and R documentation updates

After pulling this repo, do:

```bash
git config --local core.hooksPath ".github/prehooks"
chmod +x .github/prehooks/pre-commit 
```

