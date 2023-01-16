# Getting Started with CSE 15L on MacOS


**Installing Visual Studio Code**


To install Visual Studio Code, getting to the VS Code webpage and downloading install packages for your system would be the easiest.

>[VS Code Front Page](https://code.visualstudio.com/)

* If you scroll down on that page you will find the following downloadable files.

![1](https://user-images.githubusercontent.com/66867608/212767940-9e67640f-567e-46cf-bdce-c50a3daddaff.png)

* Take close attention to which file you chooes to download as you want to download compatible file to your OS. For me it was Mac10.11+.zip 


**Getting Connected to CSE15L Labs**

Getting Connected requires you to open a terminal in VS Code after successfully installing VS Code.

* Then from the VS Code's upper toolbar search Terminal, click open new terminal and make sure it's on bash not zsh.

* On that terminal you input 

>ssh cs15lwi23___@ieng6.ucsd.edu (___ must be the last 3 digits of your CSE15L ID)

* If successful you would get the following output from the terminal

![2](https://user-images.githubusercontent.com/66867608/212768927-752f63e9-575e-4a31-9f0b-81c79e87b839.png)

Now you are in the cs15lwi23 remote directory.

**Running Commands**

In this directory you can run commands as if you are working with your local terminal. I tried to see if I'm allowed to modify cs15lwi23.

So, I tried following lines.

> * pwd
> * cd ..
> * ls
> * mkdir

pwd was used to know my current directory, then I used cd .. to get to cs15lwi23, find out what we had at that time then tried to create a new directory.

<img width="1585" alt="abc" src="https://user-images.githubusercontent.com/66867608/212769612-615cae15-f0dc-4943-85a0-e14a14ab20e8.png">

I was able to know that all the last three digits of the accounts of CS15L start with 'a' and I was not allowed to create a new directory "test"

It was interesting how I was able to know all the addresses of the students while I have no permission to do anything with it. 

Wouldn't it be possible to not show things that I have access to?

