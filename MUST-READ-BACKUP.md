# Backup from work Mac — 2026-09-30

- Original local path: `/Users/muhammadmohsin/Documents/Learning/wedding-invitation`
- Checked-out branch: `public-one`; HEAD: `3d6a313d44b5373c14469321bf25683e7875fdc0`
- Snapshot contents: current HEAD plus all uncommitted and untracked (non-ignored) changes; 0 new/changed files included vs HEAD.

## Backup branches pushed (intended)
- `backup/work-mac-2026-09-30` (snapshot)
- `backup/branches/4.x`
- `backup/branches/dev-branch`
- `backup/branches/public`
- `backup/branches/public-one`

## Excluded files (paths only)
Copy these manually from a secure source if needed.
- (none)

## Restore
```
git clone https://github.com/mohsinsapra/wedding-invitation.git && cd <repo>
git fetch origin 'refs/heads/backup/*:refs/remotes/origin/backup/*'
git checkout -b restore origin/backup/work-mac-2026-09-30
# then merge/cherry-pick into main when ready; stashes are under origin/backup/stash-N
```

Nothing has been merged into main yet.
