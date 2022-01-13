## What is Continuous Integration?
**Continuous Integration is a software
development practice in which
developers are required to frequently
commit changes to the source code in
a shared repository. Each commit is
then continuously pulled & built.
Jenkins is an open source, Continuous
Integration (CI) tool, written in Java. It
continuously pulls, builds and tests any
code commits made by a developer
with the help of plugins.**

## Install Jenkins On Ubuntu
***This installation is specific to systems operating on Ubuntu.***
#### Follow the below steps:
Step 1: Install Java
```
$ sudo apt update
$ sudo apt install openjdk-8-jdk
```

Step 2: Add Jenkins Repository
```
$ wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key
| sudo apt-key add –
```
Step 3: Add Jenkins repo to the system
```
$ sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable
binary/ > /etc/apt/sources.list.d/jenkins.list’
```
Step 4: Install Jenkins
```
$ sudo apt update
$ sudo apt install Jenkins
```
Step 5: Verify installation
```
$ systemctl status Jenkins
```
Step 6: Once Jenkins is up and running, access it from the localhost default port 8080
[link](http://localhost:8080)
