ECE 2021

AUTHORS:
Emilie Murphy
Keziah Joseph


Important Topics - Part 1 (Working locally):

1. Git Tracks Your Work in 3 Areas

Git uses three logical areas to manage changes:
	•Workspace (Working Directory) – where you edit files
	•Staging Area – temporary area where you prepare a “group” of changes
	•Local Repository – where commits are permanently stored

2. Initializing a Repository (git init)
	•You create a folder and then turn it into a Git repository using git init.
	•A hidden .git folder is created, which contains Git’s internal information.

3. Staging Changes (git add)
	•When you add or modify files, nothing is committed until you stage them
	•Use: git add file.txt and git add .
	•git add . stages all new and modified files.

4. Committing (git commit)
	•A commit takes a snapshot of staged files and saves them to the local repository
	•Always include a commit message, for example:
                - git commit -m "added names"
        We can also stage and commit together: git commit -a -m "message"

5. Checking Status (git status)
	•Shows what’s changed, staged, or not staged
	•One of the most frequently used commands.

6. Viewing History (git log)
	•Shows previous commits and commit messages
	•git log --oneline gives a shorter view


7. Undoing Changes

 Git has multiple ways to go backward:
	•git restore – undo working directory changes
	•git reset – move branch pointer back (can be dangerous)
	•git revert – makes a new commit that cancels an old one (safer)


8. HEAD Pointer
	•HEAD points to your current branch and commit
	•When “detached HEAD” happens, you are viewing an old commit without a branch

9. Branching
	•A branch is just a pointer to a commit
	•You can create a new branch and try changes safely using: git checkout -b branchname

10. Merging
	•Used to combine work from different branches into one
	•Git highlights merge conflicts when two versions change the same text


Important topics – part 2 (working remote)
1.	Github uses
	creating repositories in github 
	inviting collaborators 
	kanban board

2.	Useful commands 
	clone
	push
	pull
