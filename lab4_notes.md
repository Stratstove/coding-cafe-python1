1) "--global" probably refers to a global directory, or a way to access any file in any directory. Without it, perhaps it would
be difficult to access any/all files without using PATHs. (Actual - --global allows you to configurate settings across all Git 
repositories, not just the current one. without it, to configure all repositories would be a manual task).

2) With ls -a, i was able to see hidden files like .git and .venv . 

3) 3 files - README.md, lab4_notes.md, and the directory week02. 

4) nothing disappered, but that's because i didnt have the issue of 1000 files under .venv/ when i initally did status for git

5) now, .gitignore needs to be committed, because its possible for files that need to be ignored in the future. 
 
6) in the git status Output, README.md moved from "Untracked files" to "Changes to be committed". Here, relative to 3 places
model, it has moved from "Staging Area" to "Working Repository"

7) After commit, the output was the "title" (analogous). Then, 4 files changed, with 244 insertions. 

8) The first 7 characters are: 95b67d1. They are most probably an unique identification for my commit. 

9) checked the status of the git repositories; added the new notes file into "Working repository"; then commited the new notes
file; then checked the commit ID. 

10) because README is not part of any other repository (lab4/notes.md is part of lab4/ repository, for example)

11) it provided me with an OTP

12) Currently it shows me the README file on the front page, and thats because its the only "file" in the repository (everything
else is a nested repository). 

13) Local history now contains origin/master

14) If a repository is private, only I can continuously track additions to files and repositories. But if there is
no repository, there is no way for me to "efficiently" track my additions and changes. 
