---
title : Set pytorch environment (ubuntu20.04, anaconda)
date : 2022-11-06 22:00:00 KST
categories : [Development, Environemtn]
tags : [pytorch,anaconda] #소문자만 가능
---

1. Create anaconda environment – python version 3.7
```bash
$ conda create -n <env_name> python=3.7
  ex) conda create -n my_env python=3.7
```
1. Check pytorch and torchvision version in pytorch channel
```bash
$ conda search -c pytorch pytorch |grep 37
$ conda search -c pytorch torchvision |grep 37
```
1. Install pytorch
* If you install torchvision, anaconda will install the appropriate version of pytorch.
```bash
$ conda install -c pytorch pytorch=<version>=<release>
  ex) $ conda install -c pytorch pytorch=1.12.1=cuda111py37he43340c_201
```
