Q1) pwd refers to 'print working directory' - it shows exactly under which folder/set of folders i am present in. 
Q2) 'ls -a' showed me the extra, hidden files, which 'ls' did not. 'ls -a' showed those files used by the OS to operate/move around in the folder
Q3) 'ls -l' shows me more details about the files, including the file permissions, owner name(s), last modified date/time and file name itself. 
Q4) using 'ls coding-cafe-python/week02' first takes me to coding-cafe-python folder, then to week02 folder, which houses notes.md file. here, this is a relative path.
Q5) in command 1, mv moved the 'README-backup.md' file into 'week01' directory. in command 2, mv renamed 'README-backup.md' into 'old-readme.md'
Q6) I have exactly 22 folders
Q7) My python3 is stored in '/usr/bin/python3'
Q8) (To be done) 
Q9) when I typed in 'pyton3', it said 'command pyton3 not found. Did you mean python3?'. What this might imply is: under the 'coding-cafe-python' directory, the terminal was not able to fetch any directory/file with the name 'pyton3'. I.e. the path of 'pyton3' was not found. 
Q10) .venv didn't appear with plain ls because .venv is a hidden file. 
Q11) a new line/phrase (.venv) appeared before my normal prompt. 
Q12) currently, python is stored in '/home/stratstove/coding-cafe-python/.venv/bin/python3'. This is not the same path - originally, python3 was stored globally. Now, python3 is stored in this virutal environment. this makes the virtual environment 'private'. 'Activate' moved the python3 files from a global path to the private path. 
Q13) list 2 had these following additional items: certifi(ver.2026.7.22), charset-normalizer(ver.3.5.1), idna(ver.3.19), requests(ver.2.34.2), urllib3(ver.2.7.0)
Q14) Now, python3 points to the original global path.
Q15) ls-h prints out detailed size-blocks in human readable format
Q16) Ctrl+C only interrupted python3, whereas Ctrl+D completely killed and exited python3 
