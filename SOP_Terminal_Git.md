# Phase 1: Terminal & Git Cheat Sheet

## 1. Navigating the Lab (Basic Commands)
* `pwd` : "Print Working Directory" (Where am I standing?)
* `ls` : "List" (What is on the bench in front of me?)
* `cd [folder]` : "Change Directory" (Walk into a room)
* `cd ..` : Walk backwards out of a room.

## 2. Handling Tubes (File Management)
* `mkdir [folder]` : Make a new folder/rack.
* `mv [old_name] [new_name]` : Move or rename a file.
* `cat [file]` : Look at the contents of a file.

## 3. Filtering Data
* `sls "word" [file]` : Search inside a file for a specific word (like "PASS").
* `>` : The "pipette" symbol. Redirects the output of a command into a brand new file.

## 4. The Digital Lab Notebook (Git & GitHub)
* `.gitignore` : The VIP list of files Git is NOT allowed to look at (e.g., massive `data/` files).
* `git status` : Check the current state of the bench (red = untracked, green = ready to save).
* `git add .` : Glue all changes on the bench to the notebook page.
* `git commit -m "Note"` : Sign and date the page with a sticky note explaining the change.
* `git push` : Ship the updated notebook to the public library (GitHub).