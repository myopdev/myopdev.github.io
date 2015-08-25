---
layout: post
title:  "Installation Guide"
date:   2015-08-22 12:29:34
categories: jekyll update
---

# Software Requirement

1. [ToPS](https://github.com/ayoshiaki/tops)  
2. [SegSeq](https://github.com/ayoshiaki/segseq)
3. [Git](https://git-scm.com/)
4. [Perl - ForkManager](http://search.cpan.org/~dlux/Parallel-ForkManager-0.7.5/ForkManager.pm)
5. [BioPerl](http://www.bioperl.org)
6. Linux or MacOSX

# Installing MYOP

After you have installed the software requirement, you can install MYOP by following the instructions below:

* You can download MYOP from our GitHub repository.  

```
git clone https://github.com/myopdev/myop.git
```

* Copy the `myop` folder to `/usr/local/` folder.

```
sudo cp -r myop /usr/local
```

* Add the following line at the end of the `.profile` file.  

```
export PATH=$PATH:/usr/local/myop/scripts
```







