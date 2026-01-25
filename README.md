# README

## Overview
Resources for educ-project-2026

## Details


### Implement suite of Python Apps





Introduction



You will build and run some useful python applications and demonstrate at the end of the week the running applications on your computer.



(using the Mac)

You will build the python apps on the Mac and you will be using the Terminal app (see below) which is a built in application on every Mac computer to allow you to edit files from command line and also create computer programs. The Terminal app uses the linux operating system (more on this below) to setup and run your new python apps so you will need to get a bit familiar with how to use the terminal and run some basic linux commands to list, view and change files, make and change directories, install applications and run programs all from the terminal (command-line) app window.



You will also need to take some screen captures of your progress along the way so that we can review together your work and make any adjustments if needed along the way. This will also be possible to do easily from the Mac and the instructions will be provided below.



(setting up python)

To build the python apps you will need to check if the python virtual machine program is installed and running and run some tests to verify it is running properly and that it has all of the python library dependencies it needs also setup (a python library dependency is some python code libraries that are like programs in that they have python code but need a python application to use that code in it and need to be included in your python code using [import] command, more on this later).





(setting up a git source code repo)

The term ‘source code repo’ is short for ‘source code repository’ which is similar to a database used specifically for storing source code files long term but also has some extra features for getting the files out of the local source repo and putting files into the local source code repo and also to send code files from local source code repo to a remote source code repo so it can be shared with others on the internet / cloud and outside your local computer. When you finish building and testing a python application, and verified it is running on your local computer (i.e. on the Mac), the next task will be to check the python code into a local git source code repo. But first you will need to check if the git application is installed and running and run some simple tests to verify it is running properly. We’ll also go over some basic git commands to put files into the git source code repo or git repo [git add, git commit, git push] and get files out of the git repo [git checkout, git pull] - more on these commands later.



When you have completed checking in your python code to your local source code repository, you will then need to store/push the code to a remote public location in order to be able to share it with others as otherwise only people with access to your local computer will be able to view or run the code. The standard By storing the code to a remote source code repository, the code is also available to you to view or run on another computer even if your local computer is turned off. 



At each stage in the project setup and implementation, there will be a checkpoint that will simply be one or more screen captures to record some of the activities just completed and will be indicated as follows … 



>> checkpoint: 



At each checkpoint, there should be one or more images captured of the screen corresponding to a few actions just completed.



The following main tasks will need to be performed to complete the project and each main task will involve some sub-tasks to complete.

Using the Mac
Setting up python
Setting up a git source code repo
1st python app - Alarm Clock app
2nd python app - QR code app
3rd python app - Spam filter app


Hopefully by the end of the week, you will have gained a basic understanding of how to work with python from the command line and also how to manage your built and tested python code in the git source code repository.



Using the Mac

(tasks)

take a screen capture
setup the terminal window
run basic linux commands


Useful mac options and tools needed.



(capturing an image from your screen)

you can take a screen capture in the mac using the keyboard command shortcut [CMD+SHIFT+4] where your mouse pointer will change shape to indicate you can capture some of them displayed items on your screen.
To capture a section of your screen with keyboard shortcut, hold down the three keys [CMD+SHIFT+4] at the same time with your left hand, then lift your left hand and with your right hand, use middle finger on your right hand to point mouse at top left corner of where you want to capture, and with your thumb on your right hand, hold down mouse button and then drag your mouse with your middle finger from top left corner to bottom right then release your right hand  from the mouse pad to capture image 
An image preview of the captured image should appear at bottom right if screen, click on it and then close the image - this will save an image into the folder called [Desktop]
Click on Finder app (at bottom left of screen) again and you should see from left side if Finder window, the folder called [Desktop]  


>> checkpoint: completion of screen capture steps (first captured image)



(viewing a previously captured image)

on your Mac, select Finder button at bottom left of your screen to open Finder window
on the File menu at the very top of you Mac, move mouse to right of File menu and click the menu option called [View] and then click the option called [as List] - this will display a list of files including captured images with newest on top
on left side of finder window, select again the folder called [Desktop]
double click on latest file listed at top of list of files shown to open it


Using the Terminal app and linux 



(the terminal window)

there are two main types of interaction with your computer 
1) with user interface (UI) windows, for opening and using desktop applications and done mostly with mouse work and some keyboard use, that uses buttons, menus and other user interface (UI) / visual components with mouse motion and mouse clicks
2) with a terminal window also called a command line interface (CLI) window or console window, which is a text based entry only window, done mostly with keyboard work and some mouse work, no buttons, no menus, or no user interface (UI) / visual components


To open a terminal window on your mac, go to the bottom left of screen (beside Finder app) to app called [Launchpad] and select the Terminal app.



(some terminal linux commands)

Setting up and using the Terminal:

the terminal box when open, displays a cursor (grey rectangle beside [%] symbol), which is an indication to type something in order to perform some action.
the terminal is running the linux operating system in the background which is the most popular operating system in the world and is similar to the Microsoft windows operating system but completely works by command line (typing commands from the terminal) and is open-source which means it is completely free to use and was invented by a very smart engineer from called Linus Torveld (hence the name linux)
On the mac terminal, a slightly modified version of linux is running that is called [darwin linux] but it is basically the same as free linux in how to use it and perform actions 
Actions can include :
checking what current directory ( folder ) you are in [pwd]
listing files and sub-folders in your current directory (directory is the same as folder) [ls | <some directory>]
changing to a different directory [cd <other-folder>]




Setting up python

(TODO)



Setting up a git source code repo

(TODO)



1st python app - Alarm Clock app

(TODO)



2nd python app - QR code app

(TODO)



3rd python app - Spam filter app

(TODO)




### git stuff

- create a new repository on the command line
```
echo "# educ-proj-resources" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/alanpmullane/educ-proj-resources.git
git push -u origin main
```

- push an existing repository from the command line
```
git remote add origin https://github.com/alanpmullane/educ-proj-resources.git
git branch -M main
git push -u origin main
```


