# Hi, This is from  local Repo

Git Configer

Git config --global user.name “my name”
Git config --global user.email someone@gmail.com  rbalochsara42@gmail.com
Git config –list






Global configuration
Local configuration   spasific project in a saparater account login



Clone & Status
Clone- Cloning a repository on our local maction
Remote           local 
[GitHub]-----------[laptop] use clone command 
HTTPS  copy link and in terminal control+v paste link
Git clone <- project  link->

Status – displays the state of the code 
Git status






It gives you a summary of the current state of your repository, helping you track changes, staged files, and untracked files. Here’s what it does in detail:

2 step process of after change in your project

Step 1:  Add 

2nd : commit

Untrack file
New file that git doesn’t yet track
Which is uncommit or doesn’t add that is untrack or modify file
Modified
Changed 
Staged
Untracked & modified file on add 
Now these File is ready to be committed

When  commit status will be unchanged
When we commit that is save and tracked & unchanged
Unmodified
Unchanged

Add & Commit
How to track file 
Add
Adds new or changed file in your working directory to the Git staging area.
Git add <-file name->
Commit
It is the record of change
Now commit
  Git commit -m “some message”
Message should be meaning full name if you fix bug then message name will be bug fix 
If add new functionality in project then message name should be functionality name if add payment method then name “payment method”

Now commit
  Git commit -m “some message”
Now check status
Git status
Terminal show 
nothing to commit, working tree clean
but by 1 commit means
this code in our local system as compare to before status. It does  not show on our github repository
for this purpose we use 
Push Command
Push – upload local repo content to remote repo



Command
  Git push origin main
Now enter if try 1st time with vs code then vs code ask us a permition
Then allow
Authorize GitHub for vs Code
Origin ->  if clone any repo or project, origin refer to that remote repo or project which we clone
In simple that clone/remote repo or project we set it’s name “origin” 
Main -> “main” is our branch 

All above the method for any clone repo or project continiue and create or add new functionality 
In vs code or local system new folder
In vs code or local system new folder which create your own code not any clone 
Use this method..
Init Command
Init – used to create a new git repo
Git init 
Git remote add origin <-link->
Git remote -v   (to verify remote) 
Git branch (to check branch)
Git branch -M main (to rename branch)
Git push origin main
Create new folder
In vs code terminal or cmd
•	mkdir   folder name
•	cd folder name above you create
•	 for example folder name “local_repo”
•	Cd local_repo
•	--     ls -a  (show . .. bcz we have yet not create any thing) yet not git repo
•	Git init (initilase git repo)
•	-  ls-a (now have to see   .   ..   .git) means now it is a git repo
•	create a file in which code (vs code show U) untrack file)
•	git status (untrack file)
•	git add  .


•	git status (show new file : file name(it’s a file which you create) 
•	git commit -m “Add initial file” (for commit in local system)
•	this project or repo is now in our local system but now we want to upload o repo or project in gighub
•	for this we create a repo on maunvaly on git hub -> create new repo
•	git remote add origin <- link->  (git remote means ju repo ham ny bnai hy osy add kro os ka name ham origin rakhty hain link add krty hain link git hub pe jb repo create ki tu o sky bab repo link bhi show hota hy osy copy kr ky command/cmd terminal pe paste kr dety hain)


•	 git remote add origin git@github.com:Sara-Aziz074/lolcal_sys_proJ_repo.git
•	For verification 
•	Git remote -v (to verify remote)
•	Git  branch ( to check branch) means abhi kon se branch pe hain 
•	Git branch -M main  (Rename branch name ) 
•	Git branch (check konsi branch pe hain)
•	Git push origin main (origin branch name)
•	Or   git push -u origin main (next time same repo code want to push 
•	every time  you doesn’t  use origin main  that’s why  “-u” flag auto update/ up streem
•	add new file “read me”
•	git status
•	git add 
•	git commit -m “ADD readme”
•	now git puch
•	
•	
Work Flow
•	Local git
1	 Local Git 
2	Create Git Hub repo
3	Clone step 2 repo file
4	Changes 
5	Add changes
6	Commit
7	Push on git hub
•	Git Branches
If multiple people work on same project then each person copy main branch and then create own branch and work in own branch
After down its work then merge
 its own work on main branch
Each person follow this process
•	Git branches Commands
1	git branch (to check branch)
2	git branch -M main (to rename branch)
3	git checkout <- branch name->  (to navigate)
4	git checkout  -b <-new branch name->  (to create new branch)
5	git branch (show all branches)
6	git checkout main  (after checkout write that branch name where you want to go
7	git branch (you have in main branch)
8	git checkout -b <-new branch name->   (create 1 morwe new branch )
9	git branch       
10	git branch -d <- branch name-> (to delete branch)
11	if delete branch then checkout branch then delete those branch which you want 
12	git checkout main (outside of feature_2 branch then you can delete branch feature_2)
13	git  branch
14	git branch -d feature_2
15	git branch (show 2 branches main, feature_1)
16	 git checkout feature_1  (go to feature_1 branch)
17	Git branch (now we are at feature_1, now changes do here)
18	Git status(After change in the file) (modified: index.html)
19	Git add .
20	Git commit -m “Add greet”
21	Git status (on branch feature_1)
22	Git checkout main
23	Git checkout feature_1
24	Git push origin feature_1
25	Git status
•	Merging Code
1.  way_1
i.	git diff <- branch name->  (to compare commits, branches, files & more)
ii.	git merge <- branch name->  (to merge 2 branches)
2.   way_2

create a PR (is a pull request) through github
Pull Request
When you push your code (work on which functionality you create it would be pull not push when moer people work on same project then pull it not push
It lets you tell others about changes you’ve pushed to a branch in a repository on GitHub.

1st review our code mean PR if our code is ok not any mistake then
Senior developer decide code push or not
1.	 compare & pull request
2.	Add new feature
3.	Create Pull request
4.	It new branch add then “pull request”
5.	If we want to see all change as like github then use “pull Command”
6.	Pull command 
7.	Git pull origin main     <- git hub se code ko vs code mein lany ke lea->
8.	Used to fetch and download content from a remote repo and immediately update the local repo to match that content.
9.	Resolve Merge Conflicts 
An event that takes place when Git is unable to automatically resolve differences in code between two commits.
Git not choes 1st branche change save or 2nd branch change save

You change in main branche
then   git add .
Git commit -m “Add button”

Git checkout feature_1
Change here
Git add .
Git commt -m “add change here”
Now both branches has done changes
Git diff main




git diff main

      Undoing changes 
Case 1: staged changes
           Git reset <-file name->
           Git reset
Case 2:  commited changes (for one commit)
             Git reset HEAD¬1 tiled

Case 3 : committed changes (for many commits)
         Git reset <-commit hash->
         Git reset --hard <- commit hash  vs code  hash is code of each commit->
 
Git log  <-Check history of commit ->
              
fork

          fork is a ruf copy any project
select fork and create a name which you want to set







