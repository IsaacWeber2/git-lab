Isaac Weber
1.git version 2.32.0 (Apple Git-132)
2.	credential.helper=osxkeychain
	user.name=Isaac
  user.email=iw280620@ohio.edu
3. -bash: command: No such file or directory
4. 	Initialized empty Git repository in /Users/isaacweber/git-lab/.git/
	Isaacs-MacBook:git-lab isaacweber$ git status
	On branch master

	No commits yet

	Untracked files:
 	 (use "git add <file>..." to include in what will be committed)
		README.md
		answers.md

nothing added to commit but untracked files present (use "git add" to track)
5.	On branch master

	No commits yet

	Changes to be committed:
  	(use "git rm --cached <file>..." to unstage)
		new file:   README.md

	Untracked files:
 	 (use "git add <file>..." to include in what will be committed)
		answers.md
6.		On branch master

	No commits yet

	Changes to be committed:
	  (use "git rm --cached <file>..." to unstage)
		new file:   README.md
		new file:   answers.md
7.	On branch master
nothing to commit, working tree clean
8.		commit 41007dcf99b4d761912298acbb2cfbfef163d107 (HEAD -> master)
	Author: Isaac <iw280620@ohio.edu>
Date:   Fri May 13 15:34:08 2022 -0400
9.		On branch main
	Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
10.		commit 41007dcf99b4d761912298acbb2cfbfef163d107 (HEAD -> main, origin/main)
	Author: Isaac <iw280620@ohio.edu>
Date:   Fri May 13 15:34:08 2022 -0400
11.		! [rejected]        main -> main (fetch first)
	error: failed to push some refs to 'https://github.com/IsaacWeber2/git-lab.git'
	hint: Updates were rejected because the remote contains work that you do
	hint: not have locally. This is usually caused by another repository pushing
	hint: to the same ref. You may want to first integrate the remote changes
	hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
12.		Yes the changes were reflected

	remote: Enumerating objects: 5, done.
	remote: Counting objects: 100% (5/5), done.
	remote: Compressing objects: 100% (2/2), done.
	remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
	Unpacking objects: 100% (3/3), 713 bytes | 178.00 KiB/s, done.
	From https://github.com/IsaacWeber2/git-lab
	   41007dc..5e44374  main       -> origin/main
	Updating 41007dc..5e44374
	Fast-forward
	 README.md | 2 ++
 1 file changed, 2 insertions(+)
13.	.		..		.git		.gitignore	README.md
