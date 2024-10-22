## git
### update from upstream
```bash
   git checkout -b update-from-upstream
   git merge upstream/main
```

### merge to main
```bash
  git checkout main
  git merge update-from-upstream
```

### delete branch
```bash
  git branch -d update-from-upstream
```
