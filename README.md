# test

### Automated semantic versioning and R documentation updates

After pulling this repo, set up the pre-commit hook by running:

```bash
git config --local core.hooksPath ".github/prehooks"
```

Now, when using `git commit`:

```bash
git commit -am "test commit"
# Running pre-commit hook...
# >>  Updating R documentation...
# >>  done.
# >>  
# >>  Updating semantic versioning and date...
# >>  - latest tag is 'v1.0.1', with 26 previous commits
# >>  - testpkg pkg version set to 1.0.1.9027
# >>  - updated DESCRIPTION
# >>  - updated NEWS.md
# >>  
# [main 300b93e] test commit
#  3 files changed, 3 insertions(+), 4 deletions(-)
```
