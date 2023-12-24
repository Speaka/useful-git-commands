### Creating a new branch:

```bash
git branch <new-branch>
```

### Scenario: after trying some things on development branch reset this branch to be like master
#### get branches on current repo
```bash
git branch
```

#### get current branch to verify
```bash
git rev-parse --abbrev-ref HEAD
```

#### reset development branch to master (or another)
```bash
git reset --hard master
```

after this force push to get the remote like the local copy

```bash
git push -f
```

this list is continously expanded
