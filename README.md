# my-web-dev-note
## Overview
To devlep a web app, I will need a program (Python-Falsk) to control the logics of the app, a database (PostgreSQL) to store the data, a html-css-js (Bootstrap, fontawesome, d3.js, ajax, etc.) pack to manage the apperance.
## Installation (reference Udacity guide)
### Git (Install)

### VirtualBox (Install)

### Vagrant (Install and set up environment)

Use Git to fork, then clone, the VM configuration
Windows: Use the Git Bash program (installed with Git) to get a Unix-style terminal. 
Other systems: Use your favorite terminal program.

Log into your personal Github account, and then navigate to the fullstack-nanodegree-vm. 

From the terminal, run:

git clone http://github.com/<username>/fullstack-nanodegree-vm fullstack
This will give you a directory named fullstack that is a clone of your remote fullstack-nanodegree-vm repository. Be sure to replace your username.

### Run VM (vagrant up; vagrant ssh)
Using the terminal, change directory to fullstack/vagrant (cd fullstack/vagrant), then type vagrant up to launch your virtual machine.

Once it is up and running, type vagrant ssh to log into it. This will log your terminal in to the virtual machine, and you'll get a Linux shell prompt. When you want to log out, type exit at the shell prompt.  To turn the virtual machine off (without deleting anything), type vagrant halt. If you do this, you'll need to run vagrant up again before you can log into it. Be sure to change to the /vagrant directory by typing cd /vagrant in order to share files between your home machine and the VM.

## Local Dev
### Local Server
