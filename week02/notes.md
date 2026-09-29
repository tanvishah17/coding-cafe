1.  pwd printed /Users/tanvi which is the user folder on the mac im using

2. ls -a showed more files than ls. It showed all the hidden files starting eith dot(.) wheras plain ls did not.

3. drwx------+  38 tanvi  staff   1216 Aug 24 09:18 Desktop
this is one of the lines the ls -l command printed, i think the first column means

4. It works from where i am standing because the coding-cafe is currently inside my home folder itself. It is a relative path as im writing this path coding-cafe/week02 relative to where im standing and not giving the file location from the top file system location.

5. first mv moved the README backup into the week01 folder from the main coding-cafe folder. then it renamed that same folder to old-readme.

6. 10
7. /Library/Frameworks/Python.framework/Versions/3.14/bin/python3
8. There is no one sitting next to me, but i think that it would be different because the file location of python on their system might be different so its different in that way or it also could be that they have a different version of python maybe.

9. zsh: command not found: pyton3
i think this happened because i mispelled the word and the shell searched for the file 'pyton3' in my PATH which it could not find hence showed command not found.

10. .vent starts with a dot(.) meaning its a hidden file and only appears with the command ls -a not ls

11. The prompt changed to show (.venv) at the beginning. This shows that the virtual environment has been activated.

12. No, the path is different. Activating the virtual environment changed my PATH so that Python from the .venv folder is found first instead of my normal Python installation. Like first it was giving the path for the computer's python now its giving the path for this specific project's python.

13. The following were in the second list but on in the first:
Package            Version
------------------ ---------
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
requests           2.34.2
urllib3            2.7.0

only  pip                26.2.1 was there in the 1st as well as the 2nd list

14. It points back to /Library/Frameworks/Python.framework/Versions/3.14/bin/python3, which is the same location as before I activated the virtual environment.

15. ls -h makes file sizes easier for humans to read by using units such as KB, MB, and GB. It is usually used with ls -l to actually display the file sizes.

16. Ctrl + C interrupts or stops a running program, while Ctrl + D sends an end-of-file signal and exits programs that are waiting for input.