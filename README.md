# Git & Github
Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

# 2.	Committing Changes:
Git add, commit, and commit messages.
<img width="868" height="344" alt="image" src="https://github.com/user-attachments/assets/20436adb-3f14-4426-a2f6-9adb7f6c011f" />

# 3.Branching and Merging:
* Branching lets you create a separate line of development to work on new features without affecting the main code.

* Merging combines changes from different branches into one.
* It helps teams work in parallel and then integrate their work smoothly.

<img width="857" height="1104" alt="image" src="https://github.com/user-attachments/assets/0df7f589-ebb2-4bbe-8aa3-cfb226bafb8c" />

<img width="1090" height="1167" alt="image" src="https://github.com/user-attachments/assets/44b3460a-d563-47fc-bca3-c0eb81d4107a" />

<img width="1090" height="1167" alt="image" src="https://github.com/user-attachments/assets/d35737b5-679e-4887-aa80-c55762be8965" />

# 4.Remote Repositories:
* Remote repositories are versions of your project stored on the internet or a network (like GitHub or GitLab).
* They let multiple people collaborate by pushing (uploading) and pulling (downloading) changes.
* They keep your code safe and synced across different systems.

<img width="1031" height="1204" alt="image" src="https://github.com/user-attachments/assets/d1e2f903-c9b2-48ca-a837-ae7238901405" />

# 5.Collaborative Work:
* Collaborative work means many people working on the same project using Git.
* Each person can make changes in their own branch without affecting others.
* They share updates using push and pull commands.
* This makes teamwork easy and organized.

<img width="891" height="1052" alt="image" src="https://github.com/user-attachments/assets/5221f048-0abf-47a9-bc59-a8ca51afb419" />

<img width="891" height="1052" alt="image" src="https://github.com/user-attachments/assets/56a04f95-1b75-4e51-a120-4a4abd63da09" />

# 6.Git Ignore:
* gitignore is a special file that tells Git which files or folders to ignore.
  
* It prevents unwanted files (like logs, temp files, or build folders) from being tracked.
* Each line in the file lists a pattern of files to ignore.
* It helps keep the repository clean and focused only on important project files.

<img width="1090" height="480" alt="image" src="https://github.com/user-attachments/assets/b644838d-11ef-40ee-b893-c54c65908624" />

# 7.Tagging:
* Tagging is used in Git to mark specific points in history, usually for releases.
* It helps identify important versions like v1.0, v2.0, etc.
* Tags are like labels for commits — they don’t change once created.
* You can create a tag using git tag <tagname> and share it using git push origin <tagname>.
<img width="1012" height="343" alt="image" src="https://github.com/user-attachments/assets/839d3768-2e58-4c36-be65-2c8c415e88ee" />

# 8.Undoing changes:
# revert (safe way):
* Git revert is a Git command used to undo changes made by a previous commit  but without deleting any history.
* Instead of removing the commit, it creates a new commit that reverses the changes.

# Reset:
* git reset moves your branch pointer to an earlier commit, removing later commits.
* It can unstage or delete changes depending on the mode (--soft, --mixed, or --hard).
<img width="892" height="904" alt="Screenshot 2025-10-09 175857" src="https://github.com/user-attachments/assets/e3ea2114-66ad-4b65-9496-72aa49982a6b" />

# 9.Git hooks:
* Git hooks are scripts that run automatically when certain Git actions occur (like commit, push, or merge).
* They’re used to automate tasks such as checking code style, running tests, or verifying commit messages before changes are applied.
<img width="850" height="1077" alt="Screenshot 2025-10-09 172037" src="https://github.com/user-attachments/assets/b565cc5f-79fb-4f41-a206-a1daec2614c8" />

# 10. Submodules:
* Git submodules are used to add one Git project inside another.
* hey help link and use another repository without copying its code.
<img width="962" height="998" alt="Screenshot 2025-10-09 175131" src="https://github.com/user-attachments/assets/c0a8a60a-31c5-4f6b-8b2b-7c519fdeb425" />

# 11. Interactive Rebase:
Interactive rebase is used to edit or rearrange past commits to make the history clean and clear.
<img width="843" height="406" alt="Screenshot 2025-10-09 185231" src="https://github.com/user-attachments/assets/dcfb2427-5a46-42f4-b780-6328acd932f8" />

# 12.Stashing:
Git stash temporarily saves your uncommitted changes so you can work on something else and apply them later.
<img width="946" height="741" alt="Screenshot 2025-10-10 185526" src="https://github.com/user-attachments/assets/9a41de8b-b8a3-4385-ac80-fd4ec0d886f1" />

# 13. Git GUI:
graphical interface that lets you use Git without typing commands.
You can stage, commit, view history, and manage branches using simple buttons and menus instead of Git Bash commands.

# 14.Reflog:(Reference log)
It shows a history of all actions (commits, resets, rebases, checkouts, etc.) that have happened in your local repository, even if those commits are not visible in git log anymore. 
<img width="977" height="571" alt="Screenshot 2025-10-10 173602" src="https://github.com/user-attachments/assets/5664e1f9-c50b-4352-b52a-e0aeac892ddc" />

# 15.Bisect
* git bisect helps you find which commit introduced a bug by checking commits one by one between a good and bad version.
* It automatically tests halfway commits until it finds the first bad one.
<img width="819" height="677" alt="Screenshot 2025-10-10 180942" src="https://github.com/user-attachments/assets/1f14ddd5-2663-42c1-9601-0eaddc9e9293" />

# 16.Git cherry pick
* git cherry-pick is used to copy a specific commit from one branch and apply it to another branch.
* It helps you reuse important changes without merging the whole branch.

<img width="993" height="1043" alt="Screenshot 2025-10-10 183737" src="https://github.com/user-attachments/assets/362a9e55-634f-4b80-98d8-e14be6e9c30f" />

<img width="991" height="575" alt="Screenshot 2025-10-10 183801" src="https://github.com/user-attachments/assets/36bc2efd-1078-403a-828e-df6518b30f41" />




