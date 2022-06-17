---
title: Fun Linux Commands
data: 2022-06-17 12:32:00 -500
categories: [Linux]
tags: [linux, ubuntu, commands, fun]
---

# Fun Linux Commands

I'm trying to learn Linux - which will no doubt be useful for my future career(s). In order to mix it up a little, I thought I would write a post on 5 fun Linux commands. All of the commands in this post will be for Ubuntu, as this is what I use. 

For all of these commands, I am assuming that you havve updated your system using the following command:
```shell
sudo apt update && sudo apt upgrade
```

---
## 1. Steam Locomotive

Once installed, whenever you type "sl" into the terminal, a steam locomotive will be outputted. 

![steam locomotive](https://i.ytimg.com/vi/nsuLNVR28Hs/maxresdefault.jpg)

To install, run the following command:
```shell
sudo apt install sl
```
Once ran, you should get the following output from the terminal:
```shell
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following NEW packages will be installed:
  sl
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 12.7 kB of archives.
After this operation, 60.4 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu focal/universe amd64 sl amd64 5.02-1 [12.7 kB]
Fetched 12.7 kB in 5s (2424 B/s)
Selecting previously unselected package sl.
(Reading database ... 58706 files and directories currently installed.)
Preparing to unpack .../archives/sl_5.02-1_amd64.deb ...
Unpacking sl (5.02-1) ...
Setting up sl (5.02-1) ...
Processing triggers for man-db (2.9.1-1) ...
```
In order to see the steam loco move across the terminal, simply use the command below and press enter:
```shell
sl
```
---
## 2. cmatrix

We've all seen the Hollywood movies with the matrix style animation when actors' are hacking. Obviously, that's not *quite* how it works in real life, but we can still get that same animation in our Linux terminal.

![cmatrix](https://repository-images.githubusercontent.com/310526431/f3510580-2712-11eb-9cf2-793ab4e1bbf7)

To install, run the following command:
```shell
sudo apt install cmatrix
```
Once ran, you should get the following output from the terminal:
```shell
Reading package lists... Done
Building dependency tree
Reading state information... Done
Suggested packages:
  cmatrix-xfont
The following NEW packages will be installed:
  cmatrix
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 17.2 kB of archives.
After this operation, 52.2 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu focal/universe amd64 cmatrix amd64 2.0-2 [17.2 kB]
Fetched 17.2 kB in 6s (3083 B/s)
Selecting previously unselected package cmatrix.
(Reading database ... 58729 files and directories currently installed.)
Preparing to unpack .../cmatrix_2.0-2_amd64.deb ...
Unpacking cmatrix (2.0-2) ...
Setting up cmatrix (2.0-2) ...
Processing triggers for mime-support (3.64ubuntu1) ...
Processing triggers for man-db (2.9.1-1) ...
```
To view the animation, use the command:
```shell
cmatrix
```
---
## 3. Fortune

We've all wondered what our fortune is at times - so why not get your fortune from your terminal??
```shell
You teach best what you most need to learn.
```
To install, run the following command:
```shell
sudo apt install fortune
```
Once ran, you should get the following output from the terminal:
```shell
Reading package lists... Done
Building dependency tree
Reading state information... Done
Note, selecting 'fortune-mod' instead of 'fortune'
The following additional packages will be installed:
  fortunes-min librecode0
Suggested packages:
  fortunes
The following NEW packages will be installed:
  fortune-mod fortunes-min librecode0
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 615 kB of archives.
After this operation, 2135 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://archive.ubuntu.com/ubuntu focal/main amd64 librecode0 amd64 3.6-24 [523 kB]
Get:2 http://archive.ubuntu.com/ubuntu focal/universe amd64 fortune-mod amd64 1:1.99.1-7build1 [37.3 kB]
Get:3 http://archive.ubuntu.com/ubuntu focal/universe amd64 fortunes-min all 1:1.99.1-7build1 [55.1 kB]
Fetched 615 kB in 6s (108 kB/s)
Selecting previously unselected package librecode0:amd64.
(Reading database ... 58739 files and directories currently installed.)
Preparing to unpack .../librecode0_3.6-24_amd64.deb ...
Unpacking librecode0:amd64 (3.6-24) ...
Selecting previously unselected package fortune-mod.
Preparing to unpack .../fortune-mod_1%3a1.99.1-7build1_amd64.deb ...
Unpacking fortune-mod (1:1.99.1-7build1) ...
Selecting previously unselected package fortunes-min.
Preparing to unpack .../fortunes-min_1%3a1.99.1-7build1_all.deb ...
Unpacking fortunes-min (1:1.99.1-7build1) ...
Setting up librecode0:amd64 (3.6-24) ...
Setting up fortunes-min (1:1.99.1-7build1) ...
Setting up fortune-mod (1:1.99.1-7build1) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.9) ...
```
To get your fortune, use the following command:
```shell
fortune
```
---
## 4. aafire

Do I have any secret arsonists reading my blog? Now, I don't recommend that you go and start fires at random, physical places - but I can't see any issue with you starting a fire in your own terminal. 

![aafire](https://inconsolation.files.wordpress.com/2013/01/2013-01-12-solo-2150-aafire.png) 

To install, run the following command:
```shell
sudo apt install libaa-bin
```
Once ran, you should get the following output from the terminal:
```shell
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  libaa1
The following NEW packages will be installed:
  libaa-bin libaa1
0 upgraded, 2 newly installed, 0 to remove and 0 not upgraded.
Need to get 56.5 kB of archives.
After this operation, 242 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://archive.ubuntu.com/ubuntu focal/main amd64 libaa1 amd64 1.4p5-46 [47.3 kB]
Get:2 http://archive.ubuntu.com/ubuntu focal/universe amd64 libaa-bin amd64 1.4p5-46 [9188 B]
Fetched 56.5 kB in 5s (10.8 kB/s)
Selecting previously unselected package libaa1:amd64.
(Reading database ... 58776 files and directories currently installed.)
Preparing to unpack .../libaa1_1.4p5-46_amd64.deb ...
Unpacking libaa1:amd64 (1.4p5-46) ...
Selecting previously unselected package libaa-bin.
Preparing to unpack .../libaa-bin_1.4p5-46_amd64.deb ...
Unpacking libaa-bin (1.4p5-46) ...
Setting up libaa1:amd64 (1.4p5-46) ...
Setting up libaa-bin (1.4p5-46) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.9) ...
```
To get the fire started and your ubuntu warm, use the following command:
```shell
aafire
```
---
## 5. rig

Ever needed to generate a random identity? No, neither have I. But should you ever need to, you can using rig.

![rig](https://delightlylinux.files.wordpress.com/2016/12/rig51.png)

To install, use the following command:
```shell
sudo apt install rig
```
Once completed, you should get the following output:
```shell
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following NEW packages will be installed:
  rig
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 24.9 kB of archives.
After this operation, 79.9 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu focal/universe amd64 rig amd64 1.11-1build3 [24.9 kB]
Fetched 24.9 kB in 5s (4778 B/s)
Selecting previously unselected package rig.
(Reading database ... 58794 files and directories currently installed.)
Preparing to unpack .../rig_1.11-1build3_amd64.deb ...
Unpacking rig (1.11-1build3) ...
Setting up rig (1.11-1build3) ...
Processing triggers for man-db (2.9.1-1) ...
```
To generate a random idenity, run the following command:
```shell
rig
```
N.B: You can also generate multiple identies at once, or only have male/female identities, using the following commands:

Many Identities (M or F), "n" being the number of identities you want to be generated:
```shell
rig -c n
```
For exclusively M or F identities:

Male:
```shell
rig -m
```
Female:
```shell
rig -f
```
For an outputted list of 6 male identities, for example:
```shell
rig -c 6 -m
```
---

And with that, it brings me to the end of my first proper blog post on this site, out of many to come (I hope!). I appreciate you taking the time to read this article :)

nturneruk