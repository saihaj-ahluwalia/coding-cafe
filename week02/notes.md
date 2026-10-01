1. pwd prints the present working directory, or the current folder im inside, and the path to it.
Path
----
C:\Users\Saihaj Ahluwalia\Documents\PLAKSHA\coding\codingcafe

2. ls prints the list of all files in your current directory. Since I ran this command in the current folder it only shows my current notes.md file. 

Directory: 
C:\Users\Saihaj Ahluwalia\Documents\PLAKSHA\coding\codingcafe


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         8/27/2026   4:02 PM            176 notes.md

ls -force shows all files, visible and hidden ones as well. its similar to the ls -a command. No hidden files in my coding cafe folder thus it gave the same result.

3. the letter under mode is an indicator of the status of the file, archived , readonly, hidden, etc.

4. ls coding-cafe\week02 is a relative path as it is present INSIDE the documents section in my pc. if i was standing in another folder, say my Downloads, this command would not work since this directory is not present there.

5. mv was used to move the file from one folder or location to another as well as renaming a file (example : mv oldfile.py newfile.py)

6. The folders on my PATH :
C:\WINDOWS\system32
C:\WINDOWS
C:\WINDOWS\System32\Wbem
C:\WINDOWS\System32\WindowsPowerShell\v1.0\
C:\WINDOWS\System32\OpenSSH\
C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common
C:\Program Files\NVIDIA Corporation\NVIDIA App\NvDLISR
C:\Program Files\dotnet\
C:\Program Files\Git\cmd
C:\MinGW\bin
C:\Program Files\Cloudflare\Cloudflare WARP\
C:\Users\Saihaj Ahluwalia\.local\bin
C:\Users\Saihaj Ahluwalia\AppData\Local\Microsoft\WindowsApps
C:\Users\Saihaj Ahluwalia\AppData\Local\Programs\Microsoft VS Code\bin
C:\Users\Saihaj Ahluwalia\AppData\Local\Python\pythoncore-3.14-64\Scripts

7. C:\Users\Saihaj Ahluwalia\AppData\Local\Python\pythoncore-3.14-64\Scripts

8. The person next to me had python directly installed in the Users folder while mine follows the entire pathto localfiles.

9. pyton : The term 'pyton' is not recognized as the name of a cmdlet,
function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try
again.
At line:1 char:1
+ pyton
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (pyton:String) [], CommandNo
   tFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

10. .venv didnt show up with plain ls and its a hidden file while it does show up with ls-force command.

11. -Scope CurrentUser only affects current account, not the whole computer, and I did not need administrator rights. Thus running the prompt again worked.

12. Get Command Python now shows .venv in the path as well. this shows that the "box" has been created which creates a new path for the file.

13. the first pip list only showed basic pip files and libraries i had already installed such as numpy and matplotlib . after downloading requests it started to show all additional files such as certifi  charset-normalizer idna and requests.

14. deactivate removes the .venv closed environment and shows python exactly where it was in my computer.

15. the -Recurse flag is attached to several commands. ls -recurse enters each and every directory at a deeper level and shows path of all files i used the "get" command on. so instead of showing, say, 3 folders  inside a given folder, itll show all the folders AS WELL AS the files inside them.

16. ctrlc forcefully stops a running program, technically KILLS it
    ctrlz asks the program to stop temporarily and wait for user input before running back again.
