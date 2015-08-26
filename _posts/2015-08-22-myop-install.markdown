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

After you have installed the required software, you can install MYOP by following the instructions below:

1. MYOP is available from our GitHub repository.  

   ```
   git clone https://github.com/myopdev/myop.git
   ```

2. Copy the `myop` folder to `/usr/local/` folder.

   ```
   sudo cp -r myop /usr/local
   ```

3. Add the following line at the end of the `.profile` file.  

   ```
   export PATH=$PATH:/usr/local/myop/scripts
   ```







