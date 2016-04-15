---
title: Prediction
layout: doc
---

# Prediction

First you need to choose which model you want to use. To list all available models type `myop`. It will show you something like:

```
|--------------------------------|
| MYOP - Make Your Own Predictor |
|          version 1.0.0         |
|--------------------------------|

Available programs:
  * myop-predict
  * myop-train
  * myop-add-genome
  * myop-add-transcriptome

Available genomes:
  * A.thaliana
  * C.elegans
  * D.melanogaster
  * D.rerio
  * H.sapiens
  * M.musculus
  * O.sativa
  * P.falciparum
  * R.norvegicus
  * Z.mays

Available transcriptomes:


```

In this case, there are 10 available genomes and you can choose any of them.

So, if you have a sequence called `seq1.fa` and you want to use the human model, type:

```
myop-predict -g H.sapiens -f seq1.fa
```

For more help, try:

```
myop-predict --help
```
