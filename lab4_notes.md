1) "--global" probably refers to a global directory, or a way to access any file in any directory. Without it, perhaps it would
be difficult to access any/all files without using PATHs. (Actual - --global allows you to configurate settings across all Git 
repositories, not just the current one. without it, to configure all repositories would be a manual task).

2) With ls -a, i was able to see hidden files like .git and .venv . 

3) 3 files - README.md, lab4_notes.md, and the directory week02. 

4) nothing disappered, but that's because i didnt have the issue of 1000 files under .venv/ when i initally did status for git

5) now, .gitignore needs to be ignored, because it contains files and directories that we should not track/commit to. 
 
6) in the git status Output, README.md moved from "Untracked files" to "Changes to be committed". Here, relative to 3 places
model, it has moved from "Staging Area" to "Working Repository"

7)  
