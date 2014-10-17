First, you have to get started by downloading either the command line, or GUI.  
There are many different versions of these, but I have worked with two different ones.

This website is where I first downloaded the GUI and the command line, it comes in the same package. 
I recommend working with both to see what you like most, but in the end it is up to you.
https://windows.github.com/

This website is another commmand line version of github that I use.  For me, I have it installed on my flash drive (portable version) so that I can just plug it in and go.
http://git-scm.com/downloads
  (This is bascially the same thing as windwos.github but maybe less updated?)

From here, if you are using a GUI, you are on your own.  But still look at the next sections, because you will get the theory behind things while I explain the commands.

After downloading the command line running it should look something like either cmd termninal in windows, or a terminal in a linux based system.  

The first thing that you should do after installing and running your terminal window is run these two commands.  
These commands give your terminal your name and  your email address that it logs so that whenever you make changes to a file,
Github sees and can show that it was you that did it.  
These commands are as follows (commands taken from https://help.github.com/articles/set-up-git/)

    git config --global user.name "YOUR NAME"
    git config --global user.email "YOUR EMAIL ADDRESS"


I would reccomend on creating a directory whereever you would like to keep all of your github repositories (projects).
Do this by either using CD to change directory and MKDIR to make the directory,
or using windows explorer to navagate to the path and create the folder.  Either way, 
inside of the github terminal you have to CD to the directory that you are trying to use.  After your directory is created.

The next step is to "clone" a repository.  This is done by going to the main page of the repository 
(for example the main page for this repository is https://github.com/rxs5346/TestTogether)
 and going to the right side and copying the "https clone url".  After doing this, go back to your 
terminal and make sure you are in the directory that you would like to place the repository, run this command.
      git clone url

For example, for this repository it would be
      git clone https://github.com/rxs5346/TestTogether.git

This copies all of the files from the github server, into a local copy inside of your folder.  
(Pretty easy).  From here in the tutorial, I will show you the basic commands within the github terminal
so that you can get started with working in projects with GitHub.


Click here to go to the commands page
https://github.com/rxs5346/TestTogether/blob/develop/gitCommands.md
