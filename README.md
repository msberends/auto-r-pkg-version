# test

### Automated semantic versioning and R documentation updates

After pulling this repo, do:

```bash
git config --local core.hooksPath ".github/prehooks"
chmod +x .github/prehooks/pre-commit 
```

Now, when using `git commit`:

```bash
git commit -am "test 5"
# Updating R documentation...
# done.
# 
# Updating semantic versioning...
# - latest tag is v1.0.1, with 12 previous commits
# - version set to v1.0.1.9013
# - updated DESCRIPTION
# - updated NEWS.md
```
