# Undoing changes:
# revert (safe way):
Git revert is a Git command used to undo changes made by a previous commit — but without deleting any history.
Instead of removing the commit, it creates a new commit that reverses the changes.

# Reset:
git reset moves your branch pointer to an earlier commit, removing later commits.
It can unstage or delete changes depending on the mode (--soft, --mixed, or --hard).
<img width="892" height="904" alt="Screenshot 2025-10-09 175857" src="https://github.com/user-attachments/assets/e3ea2114-66ad-4b65-9496-72aa49982a6b" />

# Git hooks:
Git hooks are scripts that run automatically when certain Git actions occur (like commit, push, or merge).
They’re used to automate tasks such as checking code style, running tests, or verifying commit messages before changes are applied.
<img width="850" height="1077" alt="Screenshot 2025-10-09 172037" src="https://github.com/user-attachments/assets/b565cc5f-79fb-4f41-a206-a1daec2614c8" />

# Submodules:
Git submodules are used to add one Git project inside another.
They help link and use another repository without copying its code.
<img width="962" height="998" alt="Screenshot 2025-10-09 175131" src="https://github.com/user-attachments/assets/c0a8a60a-31c5-4f6b-8b2b-7c519fdeb425" />

# Interactive Rebase:
Interactive rebase is used to edit or rearrange past commits to make the history clean and clear.
<img width="843" height="406" alt="Screenshot 2025-10-09 185231" src="https://github.com/user-attachments/assets/dcfb2427-5a46-42f4-b780-6328acd932f8" />

# Stashing:
Git stash temporarily saves your uncommitted changes so you can work on something else and apply them later.
