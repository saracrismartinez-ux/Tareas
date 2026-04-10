# Tareas
Git y Github
sarac@LAPTOP-7F1LFATI MINGW64 /c/BootCamp/Modulo 3/1/Ejemplo1
$ git --version
git version 2.53.0.windows.2

sarac@LAPTOP-7F1LFATI MINGW64 /c/BootCamp/Modulo 3/1/Ejemplo1
$ git init
Initialized empty Git repository in C:/BootCamp/Modulo 3/1/Ejemplo1/.git/
sarac@LAPTOP-7F1LFATI MINGW64 /c/BootCamp/Modulo 3/1/Ejemplo1 (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)    
        assets/
        ejemplo.txt
        index.html

nothing added to commit but untracked files present (use "git add" to track)
sarac@LAPTOP-7F1LFATI MINGW64 /c/BootCamp/Modulo 3/1/Ejemplo1 (main)
$ git add .

sarac@LAPTOP-7F1LFATI MINGW64 /c/BootCamp/Modulo 3/1/Ejemplo1 (main)
$ git commit -m "Primer commit"
[main (root-commit) 68d92ed] Primer commit
 4 files changed, 194 insertions(+)
 create mode 100644 assets/css/main.css
 create mode 100644 assets/js/main.js
 create mode 100644 ejemplo.txt
 create mode 100644 index.html
