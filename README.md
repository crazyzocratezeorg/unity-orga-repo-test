# unity-orga-repo-test
I'm testing, how the org system inside github works.


so this should be seen only in the new branch for now.

But isn't... so what am I doing wrong?

AHH!! So obviously I need to commit changes.

So the workflow goes as follows:
	1. Make a new branch.
	2. From that branch (let's say 'Edit whatever') edit the file (in Unity, Sublime or whatever filetype it is).
	3. SAVE that changes to the file.
	4. COMMIT those changes to the 'Edit whatever' branch.
	5. That's it for now. Now you can see those changes only in that specific branch's file. Therefor you have two versions.

To work over several days at one file or topic it should work, if the changes on the branch won't merged into a branch on a higher level branch (like master).

Everything I need to do is open github (desktop) first and open the repository I want to work on (well technically it's ok to open github desktop after the file path, since it's only important to chose the right branch as follows). Then I have to chose the branch, where my latest file/project version lays. 
Now I can open the local file path to that file on my local machine. If all changes were commited, there should be no problems and I can work on.

Once my changes are done, i.e. if a feature is fully working within my project, and I'm happy with them I can now commit those changes to a higher level branch. This can be any branch, even the organization's project master. But it would be good measure to first commit these changes locally to the master and from there merge it into the organization's project. 

To get local changes applied to the GitHub site I need to push them. This only ensures my changes I made on the local machine and to the local GitHub Desktop app are transferred/pushed to the GitHub Server (website).