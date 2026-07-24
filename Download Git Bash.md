Go to this link https://git-scm.com/install/windows, and download the required file!

This page will also help you use Git bash. 
Comeback when welcome page tells you to!

Now we **Initialize a Repository in Obsidian**

Go to the command line on the left!
![[Pasted image 20260723234728.png]]

And type "Git: initialize new Repo"

Now navigate to the directory where obsidian vault is located 
Ex:  C:\Users\user\Documents\Obsidian Vaults\Git-Obsidian

Right click and open Git Bash
![[Pasted image 20260723235129.png]]

Type in "git remote add origin https://github.com/YourUsername/YourRepository.git"

Ex: "git remote add origin https://github.com/TheLoneGoat/Git-Obsidian-Tutorial.git"

Then verify using "git remote -v"

![[Pasted image 20260723235408.png]]

Should see something like mine below git remote -v

Now make your first commit using these two lines:
git add .
git commit -m "Initial commit"