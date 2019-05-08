# GitHub Workflow with Organizations
## This is how GitHub works.

Everything You need to do is open github (desktop) first and open the repository
You want to work on (well technically it's ok to open github desktop after the
file path, since it's only important to chose the right branch as follows).
Then You have to chose the branch, where my latest file/project version lays. 
Now You can open the local file path to that file on my local machine. 
If all changes were commited, there should be no problems and You can work on.

Once my changes are done, i.e. if a feature is fully working within my project, 
and You'm happy with them You can now commit those changes to a higher level branch. 
This can be any branch, even the organization's project master. 
But it would be good measure to first commit these changes locally to the master 
and from there merge it into the organization's project. 

To get local changes applied to the GitHub site You need to push them. 
This only ensures my changes You made on the local machine and to the local 
GitHub Desktop app are transferred/pushed to the GitHub Server (website).

So the complete workflow goes as follows:

	1. Fork the organization's project to your own account so you can work on it, 
	without getting in too much trouble for killing the project.
	2. Clone that new account-specific repo to your local machine using, i.e. 'GitHub Dekstop'.
	3. Before making any changes to the project files make a new branch and 
	name it properly (you also should give a good description of what you are going to change and (maybe) why!). 
	This step is crucial since it is the main part of your version control.
	4. Select the branch in the desktop app's branch menu. 
	By doing this you make sure, you're not in the master branch of your project repo.

 Now you can start editing your files. While editing it's important to think about 
 the necessity of creating new branches. Maybe if you want to play around with something 
 or want to follow another idea and you are afraid you might crash the whole thing 
 it might come in handy to create a new branch off of the master or whatever branch you are in.

 If you are done changing something follow these steps:

	5. SAVE that changes to the file. (In Unity, or whatever programm you are working in.) 
	Should be obvious but otherwise there won't be any changes to load to the server or the project respectively.
	6. COMMIT those changes to the LOCAL(!) branch (in your desktop app). 
	Make sure you give the commit a fitting name and description so others are able to recognize what exactly has changed. 
	It's like commenting your piece of code (which is always a good idea).
	7. PUSH the changes. This means you will upload your local repo to the server and update it. Note that the project that gets updated
	will be your personal copy of the organization's project. 
	(This might take a while, according to your bandwidth and your filesize). 
	This step is optional as long as you are working on the changes, 
	but it's necessary if you want to change something permanent.

Now you can see those changes only in that specific branch's file. 
So if you switch between branches and each time you open the same file you will have different appearences of that file.

If your changes are finished and you want to merge it into the project 
follow these steps:

	8. MERGE your working branch into your local master branch (or the next higher level branch according to the projects hierarchy). 
	This step is no necessity, but can keep your local repo more manageable. 
	After this you can safely delete the branch you were working on.
	8.5. PUSH these changes so the server gets updated.
	9. Send a PULL REQUEST to the organization's project distributor (they are like admins to the project. Only they can accept or reject pull requests).
	With your pull request you ask for merging your local changes into the organization's project.
	And again: it is important to name things properly.
