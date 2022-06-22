---
title: Install Ubuntu on WSL2
data: 2022-06-22 19:09:00 -500
categories: [Linux]
tags: [linux, ubuntu, wsl, wsl2, powershell]
---
# How to install Ubuntu on WSL2

Windows Subsystem for Linux (WSL/WSL2) is a great tool. It allows you to install most Linux terminal environments quickly and easily on your Windows OS. 

This guide will run through how to install Ubuntu on WSL, and will work for both Windows 10 and Windows 11.

## Installing WSL

Firstly, we need to install WSL itself. To do this, search for "Windows Powershell" in the search bar, and select "Run as administrator". 

Once PowerShell has opened, type the following command:

```
wsl --install
```
After executing this command, wait for it to complete.

Once finished, you will need to **restart** your machine in order for WSL to be "activated". 

## Installing Ubuntu

Now WSL itself has been installed, we need to install our Linux distro. In the case of this article, we will be installing Ubuntu.

Open the Microsoft Store app, and search for **Ubuntu**. 

Choose the version of Ubuntu you require. Personally, I would choose the latest edition, which is **20.04 LTS** at the time of writing, as this will give you the longest support period. 

Once this has installed and downloaded, search for **Ubuntu** in the search bar.

Depending on the version that you have installed, either **Ubuntu** or **Ubuntu xx.xx LTS** may appear. 

## Configuring Ubuntu

Now we have installed WSL and Ubuntu, we can start to configure and use Ubuntu.

Once you have opened Ubuntu, it will start to install (this could take a few minutes).

After it has finished installing, it will ask you to create a username and password (make sure this is strong and memorable).

After setting your login details, it is always a healthy practice to install the latest updates, using the following command (making sure to press Y when prompted):

```shell
sudo apt update && sudo apt upgrade
```
### Well done! You have now successfully installed Ubuntu on WSL. You can now install your first package(s) - why not check out my other blog post: [Fun Linux Commands](https://nturneruk.github.io/posts/fun-linux-commands/)

