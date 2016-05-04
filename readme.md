This is demo project for git.
Making a 2nd change.
  change file(will me red if modified and not added)
  git add filename
  git commit -m "note"
Atom shortcut for adding note.
    git config --global core.editor "atom --wait"
    git add filename
    git commit and atom will open
Tracking files and folders

State of a file
  untrack ; ignored by git
  tracked : git tracks changes to the file
    committed/unchanged - changes are current
    unstaged- there are unsaved changes
    staged -will be saved when you git commit
git status
git diff: detailed view of git status.
git sha(file sha): can resort back to previous changes.
