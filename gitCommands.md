So we've already learned the 
  git clone url
command, but this command basically just copies all of the files out of the repository and puts them on a local copy on your machine

After doing this, say you want to create your project within this directory.  You are free to do so, and after you create your project you might want to save what you have so far.

The first command that you would need to think of to do this would be 

git status
  This command gives you the status of files that have been changed within the directory.  At first, all of the files will be in red saying that you are not "watching" them yet.  
git add fileName
  This command adds the files to your "watched" list.  This is setting up so that you can keep versions of files that you are "watching"
git add -A - adds all of the changed files 
git add * also does this

After adding all of the files to be watched, you need to "commit" these files.  This is bascially just saving a version of what you have with a specific message of your choosing

git commit -m "this is my message about what i changed"
  This will "commit" all of the files that i am watching
  
If you would like to "push" all of your files up to the server and overwrite what is there, use this command 

git push

This will push all of your changes up to the server where others can access them.

Those are the most basic commands that you need to do with github to make revision control work, but thats boring to just have one copy of data on the server, why not increase that. From the start you have a "master" branch where you keep your main working project.  

git branch (name of branch) 
  This will create a new "branch" with all of the same files that you have so that you can make changes without changing the main copy.  This command creates the branch on your local machine.  To change to this branch, you do
git checkout (name of branch to switch to) 

(or if your starting to get the idea you can just do this one command to create the branch and switch to it automatically)
  git checkout -b (name of branch to create and switch to)
  
You can also just use this command to see the list of branches that you have created
git branch

From here, once you have your new branch created and switched to, everything is bascailly the same as the top, adding files, commiting, but there is only one thing different with the pushing.  

When pushing a branch to the server for the first time, you have to use this command to tell the server that you are creating a remote branch of the data that you are pushing.

git push --set-upstream origin branchName
(every push to this branch after this inital push is just done with git push)

So as an example of what i usually do after creating the initial project and pushing it to the server i usually do these commands in order...

git branch development (create a branch and call it development)
git checkout development
(make some changes and add some files that need handled)
git add -A (to add all of the files to be watched, or just selected individual files)
git commit -m "detailed message) (saving the files and setting a detailed message saying what i changed/fixed so that other programmers know what you did)

git push --set-upstream origin development


These are just a few of the commands tha can be used with Github. Go to the last page to conclude our demo.
https://github.com/rxs5346/TestTogether/blob/master/ConclusionFile





