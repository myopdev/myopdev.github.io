---
layout: post
title:  "Training a gene  finder"
date:   2015-08-22 13:19:20
categories: jekyll update
---

You can use the program ``myop-train.pl`` to train a new gene model.  This program receives a ``<fasta file>`` and an associated ``<GTF file>``. This program will download a template that contains a pre-configured model from a Git repository[1].  It returns a directory that will contain the trained gene model.

```
myop-train.pl -g <gtf file> -f <fasta file> -o <output directory>
```

# Tutorial 

1. Download the GTF and the Fasta file 
  * [GTF file]()
  * [Fasta file]()

2. Execute the ``myop-train.pl``

   ```
    myop-train.pl -g ce6.gtf -f ce6.fa -o celegans
   ```

# Specifying a different model template

To specify a different model template, you can use the option ``-r``

```
myop-train.pl -r <a customized model template> -g <gtf file> -f <fasta file> -o <output directory>
```


[1] The default model template is located at https://github.com/myopdev/myopTemplates.git


