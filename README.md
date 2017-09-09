# HW1

## Name: Debosmita Das     
## Unity ID: ddas5

## Code Files:
* [Vagrantfile](https://github.ncsu.edu/ddas5/HW1/blob/master/Vagrantfile) 
- File created after initializing vagrant init
- Changes made in the file:
     - The desired IP address of Ubuntu Virtual Machine is given
     - Enabled to execute the shell script configure.sh to install python2.7 on Ubuntu server.

* [configure.sh](https://github.ncsu.edu/ddas5/HW1/blob/master/configure.sh) 
- To install python2.7 on Ubuntu16.04
     - This installation of Python is required as we need Python2.7 to execute Ansible, but Ubuntu16.04 Virtual Box comes with Python3 by default.
     
* [inventory](https://github.ncsu.edu/ddas5/HW1/blob/master/inventory) 
- Username and password are specified here along with python version to be used by ansible

* [loops.yml](https://github.ncsu.edu/ddas5/HW1/blob/master/loops.yml) 
- YAML file which will be used by ansible playbook.
     - Code to execute this file: 
          brew install ansible
          ansible-playbook -i inventory loops.yml -s

* Please note:all these files should be in the same directory.
* 
## Screencast Link:
* [Click here to view the screencast of demo](https://www.youtube.com/watch?v=zyowyK9F3zg&feature=youtu.be)

## Instruction: 
 ![alt text](https://github.ncsu.edu/ddas5/HW0/blob/master/Slack.png)
* [Moodle](https://wolfware.ncsu.edu/profile/)

 ![alt text](https://github.ncsu.edu/ddas5/HW0/blob/master/Moodle.png)

## Screenshot of completed git tutorial:
Tasks completed in the screenshot below:
* Introduction Sequence
* Ramping Up
* Moving work around
* A Mixed Bag
* Advanced Topics [Extra Credits]

![alt text](https://github.ncsu.edu/ddas5/HW0/blob/master/Overall.png)


## [Hooks Script](https://github.ncsu.edu/ddas5/HW0/blob/master/post-commit "Hook Scripts Link"):

   **_Code Snippet_**
   
   #!/bin/sh
   
   open http://www.lib.ncsu.edu/
