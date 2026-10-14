# Git Toolkit

This file documents the Git undo and recovery tools I've learned. 

## Reset

- git reset --soft Head~1: undo last commit, keep changes staged
- git reset --mixed Head~1: undo last commit, keep changes in working directory (default)
- git reset --hard Head~1: undo last commit and discard all changes (dangerous!)
- Only use reset on commits that haven't been pushed

