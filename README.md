```

          ╭─────────────────────────────────────────╮
          │ Welcome to our Motion Capture Repo! :3 ╴ >
          ╰─────────────────────────────────────────╯          |\__/,|   (`\
                                                              _.|o o  |_   ) )
                                                            -(((---(((--------  
                                                                     

```
 
**Team:** Alexander Angelov, Angelika Juhasz, Gustaf Olsson, June Lyszczarz, Kimsea Alexandre Maximov
**Group 3**



 
## Folder Structure
 
- `/raw` — Untouched `.tak` files from Motive. 
- `/cleaned` — Cleaned versions of the raw takes. Active cleanup work lands here.
- `/[Assignment name]` — Final files (+ any supporting images/docs) for a specific submission. 
- `/reference` — Reference footage or notes.

<br>
  
> If you're checking this repo for grading purposes, **the current deliverable is in `/[N/A]`**.
 
<br>
 
 
## Setup

This repo uses Git LFS (Large File Storage) for big binaries (.tak exports, large videos, etc). without it, those files won't download properly when you clone, if you're using GitHub Desktop: it comes with LFS support built in as of recent versions, but it's not always enabled automatically. check by opening a terminal-free way:

GitHub Desktop → Repository menu → Repository Settings → check if LFS is listed/active. if you're not sure, safest is to install the standalone tool below too.

1. go to git-lfs.com and download the installer for your OS.
2. run it.
3. open a terminal once (Command Prompt / Terminal app) and run: `git lfs install` - this only needs to be done once per computer.
<br>
> You can check if you already installed it by running the command `git lfs version` in a terminal
<br>


**Repo Setup**
 
1. Open GitHub Desktop
2. Go to File
3. Choose Clone Repository
4. select this repo → choose a location on your computer



<br>

 
## Workflow: cleaning a take
 
1. **Claim a take on Trello.** Move the card to "In Progress" with your name, so nobody else starts the same take.
2. **In GitHub Desktop: Fetch origin → Pull**, so your local copy has everyone's latest merged work.
4. **Create a branch.** Current Branch dropdown → New Branch → name it after the take (e.g. `clean-idle-rdy`) → Create Branch. Confirm it says it's branching from `main`.
5. **Work normally in your local repo folder.** Clean the take in Motive, export the output into the `/cleaned` folder inside your local repo. 
6. **Check GitHub Desktop's "Changes" tab.** It automatically lists every file you added or modified. Write a short summary of what you did (e.g. "removed ghost markers") and click **Commit to [branch name]**. Make sure to do this often.
7. **Click Push origin** to send your branch up to GitHub.
8. **Open a Pull Request.** On GitHub.com → Pull Requests tab → New Pull Request → base: `main`, compare: your branch → Create. Add a short description of what you fixed. Assign a reviewer (sidebar → Reviewers). This makes it easy for someone to review the work before we put it in done.
9. **Move your Trello card to "Reviewing."**

<br>
 
## Workflow: reviewing someone else's take
 
1. **In GitHub Desktop, Fetch origin → Pull.**
2. **Switch to their branch** using the Current Branch dropdown. 
3. **Open the cleaned file**, review at the take. "Approving" the Pull Request should mean you genuinely looked at it.
4. **Go to the Pull Request on GitHub.com.** If it looks good, click **Approve**. If something's off, leave a comment explaining what needs fixing instead.
5. Once approved, either you or the repo admin merges the Pull Request, then clicks **Delete branch**.
6. **Switch back to `main` in GitHub Desktop and Pull**, so your local copy is back up to date.
7. Move the Trello card to **Done**.
<br>
 
## Notes
 
- **Github can't cope with merge conflicts** with these kinds of files, so this set up is aimed to avoid getting a conflict in the first place. If you do see a merge conflict- may the lord have mercy on you, the only way to resolve a conflict is to just choose if your work is the one that stay sor somone elses.
- **Always Pull before creating a new branch**, so you're not missing anyone's already-merged work.
- the raw `.tak` file in `/raw` never gets overwritten. open it in Motive, do your work, but always save/export the result as a new file into `/cleaned`, don't save over the original. 
