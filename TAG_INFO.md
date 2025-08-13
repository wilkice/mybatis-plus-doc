# Tag v3.3.2-alpha1 Created

This file documents the creation of the new tag `v3.3.2-alpha1`.

## Tag Details
- **Tag Name**: v3.3.2-alpha1
- **Target Commit**: e52e1eec9c761382582ef84ebbc4ee9d2737f555
- **Commit Message**: Update README.md
- **Created**: $(date)

## Commit Changes
The target commit contains an update to `guide/README.md` adding:
```
- 成都潇游科技有限公司
```

## Verification
Tag created successfully and points to the correct commit:
```bash
$ git tag -l
v3.3.2-alpha1

$ git show v3.3.2-alpha1 --oneline
e52e1ee (tag: v3.3.2-alpha1) Update README.md
```

## Next Steps
The tag needs to be pushed to the remote repository. This can be done with:
```bash
git push origin v3.3.2-alpha1
```

Note: The tag creation has been completed successfully locally.