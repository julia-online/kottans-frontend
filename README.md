# kottans-frontend :blue_heart::yellow_heart:

```linux
git config --global user.name "julia-online"
```
## Git Collaboration :v:

> :one: Detaching HEAD just means :black_circle: attaching it to a commit instead of a branch.
><br>
> :two: There are two primary ways to undo changes in Git -- :black_circle: git reset & git revert. 
git reset will move a branch backwards as if the commit had never been made in the first place ( (x) doesn't work for remote branches that others are using).
><br>
> :three: Git push can optionally take arguments in the form of: `git push <remote> <place>`. In order to specify both the source and the destination of place: `git push origin <source>:<destination>`. 
:black_circle: Pushing nothing to a remote branch deletes it -- `git push origin :foo`
> :information_source: *learngitbranching.js.org*

<details><summary>	:footprints: Click to expand the details - Screenshots from learngitbranching.js.org :footprints: </summary>
<br>
<details><summary> :mag: Main >> Ramping Up & Moving Work Around </summary>

![learngit_ramp_move](https://github.com/julia-online/kottans-frontend/blob/main/task_git_collaboration/learngit_ramp_move.jpg)

![learngit_ramp_move](https://github.com/julia-online/kottans-frontend/blob/main/task_git_collaboration/learngit_ramp_move_done.jpg)

</details>
<details><summary> :mag: Remote >> To Origin And Beyond </summary>

![learngit_origin](https://github.com/julia-online/kottans-frontend/blob/main/task_git_collaboration/learngit_origin.jpg)

![learngit_origin_done](https://github.com/julia-online/kottans-frontend/blob/main/task_git_collaboration/learngit_origin_done.jpg)

</details>
</details>

## Linux CLI, and HTTP :v:

> :bulb: https://linuxsurvival.com/command-list/

> :one: Linux is :black_circle: case-sensitive.
><br>
> :two: Renaming files is simply a case of :black_circle: "moving" a file from one name to another. For example, to rename file "wolves" to "coyotes", you would type mv wolves coyotes.
><br>
> :three: **HTTP Request** is made up of the following parts:
> 1. :black_circle: **REQUEST LINE** - it consists of a **verb** (**GET** - **POST** - **PUT** - **DELETE**), a path, and the HTTP version.
> 2. :black_circle: **HEADERS** (= communication format); - `Connection`: used to decide if the network connection needs to be closed or open once a request is completed. Possible values are `keep-alive` or `closed`.
> 3. :black_circle: **BODY** (optional) (= form submission);
> :information_source: *linuxsurvival.com & code.tutsplus.com* 

<details><summary>	:footprints: Click to expand the details - Screenshots from Linux Tutorial :footprints: </summary>

![linux_cli_done](https://github.com/julia-online/kottans-frontend/blob/main/task_linux_cli/linux_cli_done.jpg)

</details>

## Git & GitHub :v:

> :one: Git thinks about its data like a :black_circle: **stream of snapshots**.
> <br>
> :two: Git has three main states where the local files can reside: :black_circle: **modified, staged, and committed**.
> <br>
> :three: Git uses :black_circle: **HEAD** as the symbolic name for the currently checked out commit.
> :information_source: *git-scm.com*

<details><summary>	:footprints: Click to expand the details - Screenshots from learngitbranching.js.org :footprints: </summary>
<br>
<details><summary> :mag: Main >> Introduction Sequence </summary>
  
![learnGit_introSeq](https://github.com/julia-online/kottans-frontend/blob/main/task_learn_git/learnGit_introSeq.jpg)

![learngit_introseq_done](https://github.com/julia-online/kottans-frontend/blob/main/task_learn_git/learngit_introseq_done.jpg)
  
</details>
  
<details><summary> :mag: Remote >> Push & Pull </summary>

![learnGit_introSeq](https://github.com/julia-online/kottans-frontend/blob/main/task_learn_git/learnGit_pull_merged1.jpg)

![learnGit_introSeq](https://github.com/julia-online/kottans-frontend/blob/main/task_learn_git/learnGit_pull_merged2.jpg)

![learnGit_introSeq](https://github.com/julia-online/kottans-frontend/blob/main/task_learn_git/learnGit_pull_done.jpg)
  
</details>