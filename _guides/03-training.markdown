---
title: Training
layout: doc
---

# Training

You can train your own models. All you need is some annotated genes where the genomic sequence should be a (multiple) FASTA file and the annotation file should be a GTF file.

The following command trains a new model and stores it in the folder `my_model`:

```
myop-train -g seq1.gtf -f seq1.fa -o my_model
```

After that you can do predictions using this new model:

```
myop-predict -g /Path/To/my_model/ -f seq1.fa
```

You can also add it to your instalation:

```
myop-add-genome /Path/To/my_model/
```

and then use it like any other pre-installed models:

```
myop-predict -g my_model -f seq1.fa
```

If you want to remove a model, just type:

```
myop-rm-genome my_model
```