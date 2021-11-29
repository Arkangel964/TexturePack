# TexturePack
This is the github for the ligmau minecraft texture pack! If you're seeing this, congrats! You made it this far!
Unfortunately, it gets a little harder from here. I've written this tutorial to explain to you the basics of github, but if it's being dumb then just @ me on discord and i'll try to help.

Oh also, this tutorial is gonna be for windows, because that's what I use, if you use mac, I'll be posting the original documentation from each step so you can go to those links and follow the mac instructions. However, most of the documentation is the same for the github commands.

STEP 0: INSTALL GIT
You can install git from this website if you don't already have it, and there's a full tutorial there for both mac and windows. I'm not going over this part, if you have issues with the installation you can contact me.
Guide: https://www.atlassian.com/git/tutorials/install-git

STEP 1: CLONING THE REPOSITORY (you only need to do this once!)
You're gonna need to get the repository on your desktop to actually work on the files. On the start menu, type in cmd, and open up command prompt. I know this probably looks scary if you aren't a programmer, but you can do it. ![image](https://user-images.githubusercontent.com/73854594/143933744-b8a61e65-f589-43aa-b619-e33e79912a01.png)
Once you're in command prompt, grab the directory to the folder you want to store the files in. For me, i'm putting it in a folder with this directory: 
C:\Users\(my name)\Downloads\Oh-no-resource-pack
But you can put it in any folder. To get to this folder in command line, just type "cd (directory name)"
Important note: This next step will download the files from the repo to your folder. Fair warning, this repository contains all of the minecraft textures, so it's a little big. If your computer is slow, make sure you're willing to download all this stuff.
For instance, I would type "cd C:\Users\(my name)\Downloads\Oh-no-resource-pack" and that gets us into the folder. From here, type in:
"git clone https://github.com/Arkangel964/TexturePack"

Congrats! That's step 1 done.
Source for step 1:
https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

STEP 2: MAKE WHATEVER CHANGES YOU WANT TO MAKE
This one is pretty self-explanatory. Just edit the textures you want to edit! Pro-tip: If you want to know which textures haven't been edited yet, on the github page next to the file name, it'll say "Initial commit (if you're seeing this, this file is unchanged!)" If it doesn't say that, someone has probably made some changes to the file.

STEP 3: PUSH YOUR CHANGES TO THE REPOSITORY
To push your changes to the repository after you've edited files, type "git add ." to add all the files to the stage (i'm not explaining what the stage is.) Then, type: 
git commit -m"message goes here"
Except replace the part where I wrote "message goes here" with whatever you want to put as the commit message. It'd be great if your message could include what you changed for future documentation.
Finally, type in: "git push" and it should work. If it doesn't work, try doing "git push origin main" and it should work. If it still doesn't work, then contact me on discord and we'll work it out.

STEP 4: PULL FROM THE REPOSITORY
The next time you want to work on it, just navigate to the folder as you did in step 1, but rather than doing git clone, type in: "git pull"
This will give you the latest files. If you don't do this every time you start working, you'll get issues when you try to push your changes.

Whenever you want to make changes, you'll have to do step 4, then step 2, then step 3. You'll never have to repeat step 1.
Hopefully this helps!
