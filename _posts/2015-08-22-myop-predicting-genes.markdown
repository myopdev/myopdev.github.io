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

1. Download the _H. sapiens_ gene model

   [Pre-trained hsapiens model]()

2. Download an example of fasta file

   [Example of a FASTA file]()

3. Execute the ``myop-predict.pl`` program

   ```
   myop-predict.pl -p hsapiens -f test.fa > out.gtf
   ```






