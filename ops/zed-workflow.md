# Zed Workflow (ai-manifesto)

## Daily loop

1. Open Zed in repo root.
2. Edit:
   - paper/draft.md
   - paper/references.md
   - theory/, design/ as needed
3. Git:
   - git status
   - git add .
   - git commit -m "..."
   - git push origin main

## Release loop (Zenodo)

1. Ensure draft.md is consistent.
2. Update version in:
   - paper/draft.md (if mentioned)
   - ops/zenodo.md
3. Tag:
   - git tag -a vX.Y.Z -m "..."
   - git push origin vX.Y.Z
4. Confirm Zenodo DOI.
