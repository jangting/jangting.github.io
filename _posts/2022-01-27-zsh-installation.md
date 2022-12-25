-
title : Install zsh (ubuntu20.04)
date : 2022-01-27 22:00:00 KST
categories : [Development, Environemtn]
tags : [zsh] #소문자만 가능
---

1. zsh?
```zsh``` is kind of unix shell. The unix shell is a script program(interpreter) that provides a CLI (command line interface) to use the interface for the unix operating system.
Since the Unix shell was developed, various shells such as bash, ksh, tchsh, and zsh have been developed.
Among them, zsh is a program that includes useful functions of bash, ksh, and tcsh, and additionally includes various new functions, plug-ins, and theme support.

Now I will explain how to install zsh on ubuntu 20.04.

2. Install zsh and required packages
```
sudo apt install zsh curl git
```

3. oh-my-zsh

oh-my-zsh is a framework for easily configuring zsh. (link)

Entering the command below downloads the oh-my-zsh installation script and proceeds with the installation.

You can set zsh as the default shell during installation.

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
