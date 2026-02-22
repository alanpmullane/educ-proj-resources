# README

## Overview
Resources for educ-project-2026

### Resources needed for the project

- alarm-clock-sound.wav
- qr code urls
- spam emails

### Useful Links
(go through these short 5 minute tutorials on the first day and again later in the week if needed for topic refresh)

- mac ios terminal overview: https://www.youtube.com/watch?v=ZkoEHvG3GI8

- linux overview: https://www.youtube.com/watch?v=rrB13utjYV4

(note, vi and vim are linux apps that are essentially the same, where vim has slightly more features than vi)
- vi editor basics: https://www.youtube.com/watch?v=4WQAF9B7HCk
- vim editor overview: https://www.youtube.com/watch?v=Hn4y-SoyKIc

(python tkinter GUI for alarm clock app - watch 1st 3 mins of video or watch rest if you are interested in more)
- basic GUI app with python tkinter library: https://www.youtube.com/watch?v=6aKmTV6eYt8

(how qr codes work)
- qr codes oveview: https://www.youtube.com/watch?v=H289YBQo7VI
- qr code gen in python: https://www.youtube.com/watch?v=wQPIN15mbMw

(how spam filter works)
- spam filtering overview: https://www.youtube.com/watch?v=_iOxylrN4Io

At end of first day, write up a brief report of what you covered throughout the day:
- how mac screen capture, terminal, linux commands and vi editor are used
- basic python setup and code and the python tkinter GUI library
- add some additional insights from the other youtube links you watched also

## Details



### Implement a suite of Useful Python Apps



Introduction

You will build and run some useful python applications on your Mac computer, for everyday tasks and demonstrate at the end of the week the running of these python applications on your computer as well as sharing the code and documentation for these applications online.




(using the Mac)

Many software engineering companies use mac computers to develop and deliver software to their customers and to public users. You will need to be familiar with some basic operations of a Mac such as using the command line terminal app, taking screen captures, editing files and running applications (apps).



You will build some python apps on your Mac computer and will use the Terminal app (see below) which is a built in application on every Mac computer to allow you to run commands, edit files from command line and also create and run computer programs. The Terminal app uses the linux kernel and operating system (linux kernel and operating system are a set of system libraries and services that interface and communicate between your your computer software programs and your computer hardware devices to help operate the computer effectively - more on this below) to setup and run your new python apps so you will need to get a bit familiar with how to use the terminal app and run some basic linux commands to list, view and update files, make and change directories, install applications and run programs all from the terminal (command-line) app window.




You will also take some screen captures of your progress along the way to review together your work and make any adjustments if needed along the way. This will also be possible to do easily from the Mac using a simple keyboard shortcut (more on this below).



(using the vi editor)

As part of using the terminal app, you will also use the built in Linux file editor [vi] to write and save your project’s python code and a README text file to document your project code. The linux application [vi] is pre-installed on all linux operating systems and allows you to create and edit code completely from the keyboard which is useful to write application code quickly. There is also a similar pre-installed linux application called [vim] which is essentially the same as [vi] and has some extra built in features including visial block formatting and can be also used if you want but [vi] editor is enough for this project.



(setting up python)

Python programming language is made up of a virtual machine, an executable program and many libraries to do different functions.

To build python apps you will need to check if the python virtual machine is running (a virtual machine or VM is like a smaller software system running inside your computer that manages its own memory and storage, file and internet access and most computer programs like python, JavaScript, etc run a VM, you don’t need to know much more than this) and that the python executable program is also installed and running, You can run a simple test to verify it is running properly and that it has all of the python library dependencies it needs for your project setup (a python library dependency is some python code libraries that make up lots of different reusable functions and are like python applications in that they have python code but need a python application to use and run that code and need to be included in your python code using the [import] command, more on this later).





(setting up a git source code repo)

The term ‘source code repo’ is short for ‘source code repository’ which is similar to a database used specifically for storing source code files long term but also has some extra features for getting the files out of the local source code repo and putting files into the local source code repo and also to send code files from local source code repo to a remote source code repo (local here means on your Mac and remote means online on github.com) so it can be shared with others on the internet / cloud and outside your local computer. 



When you finish building and testing a python application, and verified it is running on your local computer (i.e. on the Mac), the next task will be to check the python code into a local git source code repo. But first you will need to check if the git application is installed and running and run some simple tests to verify it is running properly. We’ll also go over some basic git commands to put files into the git source code repo or git repo [git add, git commit, git push] and get files out of the git repo [git checkout, git pull] - more on these commands later.



When you have completed checking in your python code to your local source code repository, you will then need to store/push the code to a remote public location in order to be able to share it with others as otherwise only people with access to your local computer will be able to view or run the code. The standard By storing the code to a remote source code repository, the code is also available to you to view or run on another computer even if your local computer is turned off. 



At each stage in the project setup and implementation, there will be a checkpoint that will simply be one or more screen captures to record some of the activities just completed and will be indicated as follows … 



> > >: checkpoint: 



At each checkpoint, there should be one or more images captured of the screen corresponding to a few actions just completed.



The following is a summary of the main tasks to be performed to complete the project and each main task will include some sub-tasks to complete.

- Using the Mac
- Setup and run python
- Setup and run git 
- Get required project files from github
- 1st python app - Alarm Clock app
- 2nd python app - QR code app
- 3rd python app - Spam filter app
- Push new projects to github


After each sub-task, you will take screen captures to record your progress (more on this below)




Hopefully by the end of the week, you will have gained a basic understanding of how to work with python from the command line and also be able create some useful  python applications and store and manage your built and tested python code in a git source code repository.



Using the Mac

(tasks)

- take a screen capture
- view a previously captured image
- setup the terminal window
- run some linux commands
- use the vi editor


Useful mac options and tools needed.



(take a screen capture)

you can take a screen capture in the mac using the keyboard command shortcut [CMD+SHIFT+4] where your mouse pointer will change shape to indicate you can capture some of them displayed items on your screen.
To capture a section of your screen with keyboard shortcut, hold down the three keys [CMD+SHIFT+4] at the same time with your left hand, then lift your left hand and with your right hand, use middle finger on your right hand to point mouse at top left corner of where you want to capture, and with your thumb on your right hand, hold down mouse button and then drag your mouse with your middle finger from top left corner to bottom right then release your right hand  from the mouse pad to capture image 
An image preview of the captured image should appear at bottom right if screen, click on it and then close the image - this will save an image into the folder called [Desktop]
Click on Finder app (at bottom left of screen) again and you should see from left side if Finder window, the folder called [Desktop]  


> > >: checkpoint: completion of screen capture steps (first captured image)



(view a previously captured image)

on your Mac, select Finder button at bottom left of your screen to open Finder window
on the File menu at the very top of you Mac, move mouse to right of File menu and click the menu option called [View] and then click the option called [as List] - this will display a list of files including captured images with newest on top
on left side of finder window, select again the folder called [Desktop]
double click on latest file listed at top of list of files shown to open it - verify it is the latest screen capture you took


Using the Terminal app and linux 



(setup the terminal window)

there are two main types of interaction with your computer 
1) with graphical user interface (GUI) windows, for opening and using desktop applications and done mostly with mouse work and some keyboard use, that uses buttons, menus and other visual components with mouse motion and mouse clicks
2) with a terminal window also called a command line interface (CLI) window or console window, which is a text based entry only window, done mostly with keyboard work and some mouse work, no buttons, no menus, or no user interface (UI) / visual components


To open a terminal window on your mac, go to the bottom left of screen (beside Finder app) to app called [Launchpad], select [] and select the Terminal app.



(run some linux commands)

Setting up and using the Terminal:

the terminal window when open, displays a cursor (grey rectangle beside [%] symbol), which is an indication to type something in order to perform some action.
the terminal is running the linux operating system in the background which is the most popular operating system in the world and is similar to the Microsoft windows operating system but completely works by command line (typing commands from the terminal) and is open-source which means it is completely free to use and was invented by a very smart engineer from called Linus Torveld (hence the name linux)
On the mac terminal, a slightly modified version of linux is running that is called [darwin linux] but it is basically the same as free linux in how to use it and perform actions 
Actions can include :
checking what current directory ( folder ) you are in [pwd]
listing files and sub-folders in your current directory (directory is the same as folder) [ls | <some directory>]
changing to a different directory [cd <other-folder>]


(use the vi editor)

from the terminal window, edit a new file called test-hello.txt with the command [vi test-hello.txt] - this will open the vi editor with a new file called test-hello.txt and in control mode
go to edit / insert mode by typing the letter [i]
Type the sentence [hello there]
Go back to control mode by pressing the key [ESC]
Type the characters [:wq] to save the file and exit the vi editor - this will return you to the terminal window
Test the new file exists with Linux command [ls] - you should see the new file called test-hello.txt
View the contents of the new file with the Linux command [cat test-hello.txt] - this should print contents of new file, i.e. [hello there]




Setup and run python



Python is a very popular programming language for creating powerful applications and can be run in two ways :

1) by running Python code in the python console by running the command [python] and then running individual lines of code in the python console (this is useful for testing your code line by line)
2) by creating a python script file with file extension [.py], editing the python script file and adding some python code and then running the python script to execute it as a python application with a command similar to [python test-hello.py] (this is how the final working python application is typically run


(tasks)

- check python is installed
- run some python commands
- create and run a simple python app




(TODO)

(check python is installed)



(note : python will be already installed)

- check python is installed
- get python version


(run some python commands)

- run python command
- print hello
- exit python 


(create and run a simple python app)

- from the terminal window, edit a new file called test-hello.py with the command [vi test-hello.py] - this will open the vi editor with a new file called test-hello.py and in control mode 
- go to edit / insert mode by typing the letter [i]
- type the line [print ‘hello there from python’]
- go back to control mode by pressing the key [ESC]
- type the characters [:wq] to save the file and exit the vi editor - this will return you to the terminal window
- test the new file exists with Linux command [ls] - you should see the new file called test-hello.py
- view the contents of the new file with the Linux command [cat test-hello.py] - this should print contents of new file, i.e. [print hello there from python]
- run the new python app with the command [python test-hello.py] - this should print the text [hello there from python]




Setting up a git source code repo

(TODO)

(git will be already installed)



Get required files from remote git repo 

(TODO)

- alarm clock: sample wav file
- QR code : sample app urls
- spam filter: sample spam emails


1st python app - Alarm Clock app

(TODO)



2nd python app - QR code app

(TODO)



3rd python app - Spam filter app

(TODO)



Push new projects to remote git repo

(TODO)




### git repo commands

- setup ssh key
```
ssh-keygen -t rsa -b 4096 -C "<add-your-user-email-here>"
```

- after creating and accepting defaults, copy and paste id_rsa.pub contents to your github.com account'sssh keys in admin
```
cat ~/.ssh/id_rsa.pub
```

- check git user config
Run the following command to check git config and if no values or incorrect values for user.name and user.email then update to match user email used in previous step to setup
ssh key.

```
git config --global --list
```

- configure git user
Do this step only if user name and user email are not set or incorrect from previous step to check git user config.
```
git config --global user.name "<your-user-name>"
git config --global user.email "<your-user-email>"
```

- clone git repo (crete first on github.com)
```
git clone git@github.com:<username>/educ-proj-resources.git
```

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


