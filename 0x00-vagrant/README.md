# 0x00. Vagrant

## Description:bulb:
Using vagrant and source code management

* What is a zero-day
* What is a virtual machine
* What is Vagrant
* Who wrote Vagrant
* What is Ubuntu
* What does "Ubuntu" mean
* How to use VMs with Vagrant
* What does the command uname do
* What is source code management
* What is Git
* What is Github
* What is the difference between Git and Github
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code

---

## Resources:books:
Read or watch:
* [Source code management] (https://intranet.hbtn.io/concepts/22)
* [Using Vagrant on the Holberton computers] (https://intranet.hbtn.io/concepts/53)
* [Git and Github cheat sheet - Everything in less than 30 seconds] (https://intranet.hbtn.io/concepts/57)
* [The Framework] (https://intranet.hbtn.io/concepts/75)
* [Using Vagrant on your personal computer] (https://intranet.hbtn.io/concepts/81)
* [Approaching a Project] (https://intranet.hbtn.io/concepts/350)
* [Zero day] (https://en.wikipedia.org/wiki/Zero-day_(computing))
* [Virtual machine] (https://en.wikipedia.org/wiki/Virtual_machine)
* [man uname] (https://linux.die.net/man/1/uname)
* [Resources to learn Git] (https://try.github.io/)
* [About READMEs] (https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)
* [How to write a Git commit message] (https://chris.beams.io/posts/git-commit/#seven-rules)

---

## More info:memo:
**Install git**
```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

**Basic usage**
```bash
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin master
```

**Vagrant**
* Download and Install VirtualBox
* Download and install Vagrant
* Add box image for ubuntu 14.04 (Trusty), 16.04 (Xenial) or 18.04 (Bionic)
* The init command will generate a Vagrantfile
* When inside the virtual machine use logout to exit
* In /vagrant you can share files with the host
```bash
$ vagrant box add ubuntu/trusty64
$ vagrant init ubuntu/trusty64
$ vagrant up
$ vagrant ssh
$ vagrant halt
```
optional
```bash
$ vagrant box list
$ vagrant destroy
$ vagrant box remove [name-image]
```

---

## Mind Map:bookmark:
![Vagrant Mind Map](https://github.com/diegozencode/holbertonschool-zero_day/blob/master/mind-maps/vagrant-mindmap.png?raw=true)

---

## Files:card_file_box:
### [1. Hello Ubuntu](./0-hello_ubuntu)

---

## Author
* **Diego Monroy** - [diegozencode](https://github.com/diegozencode) - [twitter:speech_balloon:](https://twitter.com/diegozencode)
