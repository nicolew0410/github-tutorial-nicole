# Github Tutorial 

_by Nicole Wong_
---
## Git vs. GitHub
_Git_ is a system for version control used by programmers & runs command line on local machine & keeps track of the files & modifies it if needed (repo) 
_Github_ is a website that allows people to upload git repositories online & backups files, navigate repos & repo collaboration.

---
## Initial Setup
To make a github account you must sign up and follow the directions from the website.
In order to set up a C550 IDE, (click here) [http://github.com/hstatsep/ide50]

---
## Repository Setup

1. Cd into the right place and make a directory _cd directoryname_ _mkdir directoryname_
2. Create a README file by using _"touch README.md"_
3. Go inside the README and type something in it (It may matter or not depending) _c9 filename_
4. Save the README & exit 
5. Add the file by using _git add README.md_
6. Then commit with a message by using _"git commit -m "(message)""(Messagemust be in quotations)_
7. After that, go to your github and make a new repository name (prefarably the same name as your directory) and click create.
8. After making that, copy the 2nd line of code aka:_git remote add origin git@github.com:nicolew0410/repotest.git and git push -u origin master_
9. Finally, check if it has updated in the right place. And you're done!

---
## Workflow & Commands
Saving your work allows changes to be updated so a file's work won't be erased.
After, you would _git add (filename)_ so your work is added to the stage.
Next,  _git commit -m "message"_ so your changes would be secure and you can refer back to what you did in this version. 
Finally, _git push -u origin master_ so your work & the changes will appear on the IDE and Github.
---
### Extra Credit
With collaboration, if you want to edit someone's repo, use forking on github.com to take it into your local. After, clone the SSH site and use _git clone (website)_ to get it into your IDE. Lastly, pull requests after your changes to update your version to theirs.

---
## Feed back 
I like the different type of markdown used. 