---
layout: post
title:  "Predicting Genes"
date:   2015-08-22 12:29:34
categories: jekyll update
---

You can use the program ``myop-predict.pl`` to predict protein-coding genes.  This program receives the directory ``<model>`` of a trained gene model and a ``<fasta file>``. 

```
myop-predict.pl -p <model> -f <fasta file> > out.gtf
```

# Tutorial 

1. Download the _C. elegans_ model

   [Pre-trained _C. elegans_ model](https://drive.google.com/uc?export=download&id=0B5edlnlwsocMRHhPM3RHc3ZScmc)

2. Uncompress the tarball

   ```
   tar zxvf celegans.tar.gz
   ```

2. Download the fasta file

   [FASTA file](https://drive.google.com/uc?export=download&id=0B5edlnlwsocMT3lVMzVjNjhqSFU)

3. Execute the ``myop-predict.pl`` program

   ```
   myop-predict.pl -p celegans  -f test.fa > out.gtf
   ```






