```

          ╭─────────────────────────────────────────╮
          │ Welcome to our Motion Capture Repo! :3 ╴ >
          ╰─────────────────────────────────────────╯          |\__/,|   (`\
                                                              _.|o o  |_   ) )
                                                            -(((---(((--------  
                                                                     

```
 
**Team:** Alexander Angelov, Angelika Juhasz, Gustaf Olsson, June Lyszczarz, Kimsea Alexandre Maximov
<br>
**Group 3**



 
## Folder Structure
 
- `/raw` — Untouched `.tak` files from Motive
- `/cleaned` — Cleaned versions of the raw takes. Active cleanup work lands here
- `/[Assignment name]` — Final files (+ any supporting images/docs) for a specific submission
- `/reference` — Reference footage or notes

<br>
  
> If you're checking this repo for grading purposes, **the current deliverable is in `/[N/A]`**
 
<br>
 
 
## Setup

This repo uses Git LFS (Large File Storage) for big binaries (.tak exports, large videos, etc). without it, those files won't download properly when you clone, if you're using GitHub Desktop: it comes with LFS support built in as of recent versions, but it's not always enabled automatically. check by opening a terminal-free way:

GitHub Desktop → Repository menu → Repository Settings → check if LFS is listed/active. if you're not sure, safest is to install the standalone tool below too.

1. go to git-lfs.com and download the installer for your OS
2. run it
3. open a terminal once (Command Prompt / Terminal app) and run: `git lfs install` - this only needs to be done once per computer
<br>

> You can check if you already installed it by running the command `git lfs version` in a terminal

<br>


**Repo Setup**
 
1. Open GitHub Desktop
2. Go to File
3. Choose Clone Repository
4. select this repo → choose a location on your computer



<br>

 
## Workflow: Cleaning

1. Choose a take from Trello
2. Open GitHub Desktop → Pull
3. Do your cleanup in Motive, export the result into /cleaned inside your local repo folder
4. Write a short summary of what you did (e.g. "removed ghost markers") and Commit
5. Push
6. Hand off *the dongle*

<br>
 
## Workflow: Reviewing
 
1. Pull
2. Open the file in /cleaned in Motive and check it- play back the take, verify the fixes
3. if it's good: move the Trello card to Done
4. if it's not: move it back to "In Progress" and leave a comment on the card explaining what needs fixing, so the original person knows what to redo
<br>

 
## Notes
 
- **Github can't cope with merge conflicts** with these kinds of files, so this set up is aimed to avoid getting a conflict in the first place. If you do see a merge conflict- may the lord have mercy on you, the only way to resolve a conflict is to just choose if your work is the one that stays or somone elses
- the raw `.tak` file in `/raw` never gets overwritten. open it in Motive, do your work, but always export the result as a new file into `/cleaned`, don't save over the original
