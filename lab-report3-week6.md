# CSE 15L Lab 3

# Part 1: Streamlining ssh Configuration
* Here is the config file that was edited in VSCode and added to my .ssh folder on my computer
![Image](lab-3-pictures/sshconfig.png)

* I am now able to log in to my remote account by just doing ```ssh ieng6```
![Image](lab-3-pictures/sshieng6login.png)

* Also allowed to copy files by typing ```ieng6``` instead of my whole account email
![Image](lab-3-pictures/scpWithsshieng6.png)

# Part 2: Set Up Github access from ieng6
* Here is the public key that was made on github and its stored in my account settings
![Image](lab-3-pictures/githubsshkey.png)

* This key is stored in my user account in the ```know_hosts``` folder of ```.ssh```
![Image](lab-3-pictures/keyinremote.png)

* Able to run git commit and push on the remote server now 
![Image](lab-3-pictures/commitandpush.png)

* Here is the link to the [commit history](https://github.com/beliang/markdown-parser/commit/c4ba7b3104a657dd683bc8e29092e756f0f3646e)

# Part 3: Copy Whole Directories with scp

* Copying whole markdown directory with ```scp -r .```
![Image](lab-3-pictures/copyallscp.png)

And here are all the files in my remote after copying all 
![Image](lab-3-pictures/copiedcontents.png)

* Compiling and running junit tests on remote
![Image](lab-3-pictures/junitremote.png)

* Copying all, logging in, and running junit tests in one line

![Image](lab-3-pictures/onelinecommand1.png)
![Image](lab-3-pictures/onelinecommand2.png)
