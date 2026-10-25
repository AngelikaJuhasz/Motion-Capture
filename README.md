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


## Branches

Each assignment will have its own branch, so you will see `/A1` and `/A2` corresponding to the assignments. Current work happens in branch `/A2`

 
## Folder Structure
 
- `/raw` — Untouched `.tak` files from Motive
- `/cleaned` — Cleaned versions of the raw takes. Active cleanup work happens here
- `/[Assignment name]` — Final files for a specific submission


<br>
  
> If you're checking this repo for grading purposes, **the current assignment is in `A2`**
 
<br>

## The way we work

1. After recording the takes are uploaded it to a shared google drive, that is the master copy- those files never get altered in any way. 
2. The takes get dowloaded then uploaded to this github repo to work
3. When you sit down to work, Pull to make sure you have the most up to date version
4. If you are the first one doing the cleaning you will open up the excel sheet and double check that `take names are identical to the shotlist` and double check that `each take is starred correctly`
5. Once that is done, you are free to do your cleaning: ghost markers, swapped or missing markers. You do not trim, we will return to that.
6. Once done, you mark it on the excel sheet, and hand off *the dongle*
7. If you are reviewing, you open up each take and make sure there are no shenangans- if there are yell at the original responsible and either tell them to fix it or be the bigger person and fix it yourself under the guise of learning.
8. Once every take has been reviewed and fixed, we trim each take- we leave this step so late because if Solving is needed then we must have the T-pose still.
 
 
## Setup

This repo uses Git LFS (Large File Storage) for big binaries (.tak exports, large videos, etc). without it, those files won't download properly when you clone, if you're using GitHub Desktop: it comes with LFS support built in as of recent versions, but it's not always enabled automatically. check by opening a terminal-free way:

GitHub Desktop → Repository menu → Repository Settings → check if LFS is listed/active. if you're not sure, safest is to install the standalone tool below too.

1. go to git-lfs.com and download the installer for your OS
2. run it
3. open a terminal once (Command Prompt / Terminal app) and run: `git lfs install` - this only needs to be done once per computer
<br>

> You can check if you already installed it by running the command `git lfs version` in a terminal

<br>




 
## Notes
 
- **Github can't cope with merge conflicts** with these kinds of files, so this set up is aimed to avoid getting a conflict in the first place. If you do see a merge conflict- may the lord have mercy on you, the only way to resolve a conflict is to just choose if your work is the one that stays or somone elses.
  
- the raw `.tak` file in `/raw` never gets overwritten. open it in Motive, copy it as a new file into `/cleaned`, and work from there. IF YOU FUCKED UP: Fret not, you will take that take and put it into cleaned, then you shall visit the drive, and dowload the raw version of that take and put *that* into the raw folder.
