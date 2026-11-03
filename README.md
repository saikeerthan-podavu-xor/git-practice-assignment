cat << 'EOF' > SUBMISSION.md
# Git Practice Assignment Submission

## Part A: Rebase
- **Base Master Commit:** `4165f2c` (Update master branch)
- **Old Rebase Commit ID:** `99ef12a` (Add feature work before rebase)
- **New Rebase Commit ID:** `d2bf312` (Add feature work after rebase on master)

## Part B: Cherry-Pick
- **Source Cherry-Pick ID:** `90ffaac` (Add report commit from source-branch)
- **New Cherry-Pick ID:** `8aae63b` (Add report commit applied to team1/cherry-pick-practice)

## Repository Structure
- `master` & `team1/rebase-practice`: Demonstrates linear history rewrite via `git rebase`.
- `source-branch` & `team1/cherry-pick-practice`: Demonstrates isolating a single commit via `git cherry-pick`.
EOF

git add SUBMISSION.md
git commit -m "Add final assignment submission notes"
git push origin master
