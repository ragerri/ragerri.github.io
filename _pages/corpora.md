---
layout: archive
title: "Corpora and Datasets"
permalink: /corpora/
author_profile: true
redirect_from:
  - /datasets
  - /resources
---

{% include base_path %}

1. [CID: Catalonia Independence Corpus](#cic)
2. [Heldugazte Corpus](#heldugazte)
3. [Spanish AMR Corpus](#es-amr)
4. [QWN-PPV: Q-WordNet via Personalized PageRank](#qwn-ppv)
5. [ILF-WN: Intermediate Logic Forms from WordNet glosses](#ilf-wn)
6. [Q-WordNet: Extracting polarity from WordNet senses](#qwn)

## [Catalonia Independence Corpus (CIC) {#cic}](https://github.com/ixa-ehu/catalonia-independence-dataset)

Two datasets in Spanish (CIC-ES) and Catalan (CIC-CA) consisting of annotated Twitter messages for **automatic stance detection**. The data was collected 12 days during February and March of 2019. The corpus is annotated with three classes: AGAINST, FAVOR and NEUTRAL, which express stance towards the target, namely, the independence of Catalonia.

+ [Download the Catalonica Independence Corpus](https://github.com/ixa-ehu/catalonia-independence-dataset)

The distribution of the classes within the corpus is the following:

+ CIC-CA: 10048 tweets, AGAINST 3988, FAVOR 3902 and NEUTRAL 2158.
+ CIC-ES: 10077 tweets: AGAINST 4105, FAVOR 4104 and NEUTRAL 1868.

### Citation:

TBA

## Heldugazte Corpus {#heldugazte}

The Heldugazte Corpus contains **6 million tweets in Basque**, obtained for the **analysis of informal and formal use of Basque language in Tweets**.

+ [Download the Heldugazte Corpus](https://github.com/ixa-ehu/heldugazte-corpus)

Heldugazte is divided in two parts, the anotated corpus and the full corpus:

+ Annotated corpus: 1000 tweets (eu-heldugazte.tsv) manually annotated as *formal* or *informal*, based on the writing stile of the text of the tweet. The data is splitted into eu-heldugazte-train.tsv (650) and eu-heldugazte-test.tsv (350 tweets).

+ Full corpus: 6 million tweets in Basque from 7.977 different users, obtained during Spring/Summer of 2018. [Download Full Corpus](http://ixa2.si.ehu.es/heldugazte-corpus/heldugazte-osoa.tar.gz). The format provided is one file per user containing the IDs of every tweet by that specific user. The file is named using the ID of each user.

### Citation:

+ Joseba Fernandez de Landa, Rodrigo Agerri, Iñaki Alegria (2019). [Large Scale Linguistic Processing of Tweets to Understand Social Interactions among Speakers of Less Resourced Languages: The Basque Case](https://www.mdpi.com/2078-2489/10/6/212/htm). Information 10(6): 212 (2019).

## Spanish AMR Corpus {#es-amr}

Spanish AMR annotations for 50 sentences from the [Little Prince Corpus](https://amr.isi.edu/download/amr-bank-v1.6.txt). For more details, go to the corpus site:

+ [Download the Spanish AMR Corpus](https://github.com/ixa-ehu/amr-corpus-spanish)

### Citation:

+ Noelia Migueles-Abraira, Rodrigo Agerri and Arantza Diaz de Ilarraza (2018). [Annotating Abstract Meaning Representations for Spanish](http://www.lrec-conf.org/proceedings/lrec2018/pdf/743.pdf). In [Proceedings of the 11th Language Resources and Evaluation Conference (LREC 2018)](http://lrec2018.lrec-conf.org/en/), 7-12 May, 2018, Miyazaki, Japan.

## QWN-PPV: Generate polarity lexicons on demand {#qwn-ppv}

A new Q-WordNet version based on applying Personalized PageRanking to the original Q-WordNet approach. It is a simple, robust and (almost) unsupervised dictionary-based method (Q-WordNet by Personalized PageRanking Vector) to automatically generate polarity lexicons.

The extrinsic evaluations performed show that qwn-ppv outperforms other automatically generated lexicons. It also shows very competitive and robust results with respect to manually annotated ones. Results suggest that no single lexicon is best for every task and dataset and that the intrinsic evaluation of polarity lexicons is not a good indicator of good performance on a Sentiment Analysis task.

Our method is easily applicable to create qwn-ppv(s) other languages, and we demonstrate it by providing polarity lexicons for English and Spanish. The qwn-ppv method allows to easily create quality polarity lexicons whenever no domain-based annotated corpora are available for a given language.

+ Get English and Spanish QWN-PPV lexicons cited in the paper: [http://adimen.si.ehu.es/web/qwn-ppv](http://adimen.si.ehu.es/web/qwn-ppv)
+ Get the software from github: [https://github.com/ixa-ehu/qwn-ppv](https://github.com/ixa-ehu/qwn-ppv)

### Citation:

+ Iñaki San Vicente, Rodrigo Agerri and German Rigau (2014): [Simple, Robust and (almost) Unsupervised Generation of Polarity Lexicons for Multiple Languages](http://aclweb.org/anthology/E/E14/E14-1010.pdf). In Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics (EACL2014), April 26-30, 2014, Gothenburg, Sweden.

## ILF-WN: Automatic Generation of Intermediate Logic Forms for WordNet glosses {#ilf-wn}

A lexical resource which consists of the automatically generated Intermediate Logic Forms (ILFs) of [WordNet's glosses](http://wordnet.princeton.edu/). Intermediate Logic Forms (ILFs) include extreme neo-davidsonian reification in a simple and flat syntax close to natural language form. In its current form, the representation allows to tackle semantic phenomena such as coreference and anaphora resolution. Moreover, it can be further specified to deal with other specific semantic issues such as quantification.

Intermediate Logic Forms are straightforwardly obtained from the output of pipeline consisting of a part of speech tagger, a dependency parser and our own Intermediate Logic Form generator (all freely available tools). We apply the pipeline to the glosses of WordNet to obtain a lexical resource ready to be used as knowledge base or common knowledge resource for a variety of tasks involving some kind of semantic inference.

+ [Download ILF-WN (72M)](http://nlp.uned.es/semantics/ilf/ILFWN.v.0.2.tar.gz). A reasonably exhaustive description is also included.

### Citation:

+ Rodrigo Agerri and Anselmo Peñas (2010). [On the Automatic Generation of Intermediate Logic Form for WordNet glosses](papers/ilf.pdf). 11th International Conference on Intelligent Text Processing and Computational Linguistics (Cicling-2010), Iasi, Romania, 21-27 March. LNCS Volume 6008 by Springer.

## Q-WordNet: Extracting Polarity from WordNet senses {#qwn}

Q-WordNet is a lexical resource consisting of WordNet senses automatically classified by Positive and Negative polarity. Q-WordNet has been built for versions 1.6, 1.7, 2.0 and 3.0 of WordNet. Version 2.0 has been compared to SentiWordNet 1.0, also built from WordNet 2.0, with very promising results. Q-WordNet first version has been released for the LREC 2010, and included in the Resources Map.

A quantitative evaluation of Q-WordNet as a binary classification task shows important improvements with respect to previous approaches such as SentiWordNet.

+ Download (including reference paper): [Q-WordNet](https://ragerri.github.io/files/qwordnet-0.3.tar.gz)

### Citation:

+ Rodrigo Agerri and Ana Garcia-Serrano (2010). [Q-WordNet: Extracting polarity from WordNet senses](papers/qwn.pdf). In the Proceedings of the 7th International Conference on Language Resources and Evaluation (LREC 2010), Malta, May 2010.