---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /tools
---

{% include base_path %}

1. [IXA pipes: Ready to use NLP tools](#ixa-pipes)
2. [Opinion Target Extraction at SemEval 2015](#ote)
3. [QWN-PPV: Q-WordNet via Personalized PageRank](#qwn-ppv)

## IXA pipes: Ready to use NLP tools {#ixa-pipes}

[IXA pipes](http://ixa2.si.ehu.es/ixa-pipes) is a modular set of Natural Language Processing tools (or pipes) which provide easy access to NLP technology for several languages. It offers robust and efficient linguistic annotation to both researchers and non-NLP experts with the aim of lowering the barriers of using NLP technology either for research purposes or for small industrial developers and SMEs. The IXA pipes can be used or exploit its modularity to pick and change different components.

+ Software and documentation: [http://ixa2.si.ehu.es/ixa-pipes](http://ixa2.si.ehu.es/ixa-pipes)

### How to cite:

If you use **ixa-pipe-nerc** for Named Entity Recognition:

+ R. Agerri, G. Rigau, [Robust multilingual Named Entity Recognition with shallow semi-supervised features](http://authors.elsevier.com/a/1T5qP-c5CB15). [Artificial Intelligence](http://www.journals.elsevier.com/artificial-intelligence), 238 (2016) 63-82.

If you use **ixa-pipe-opinion** for Opinion Mining, please use this reference:

+ Rodrigo Agerri, German Rigau, [Language independent sequence labelling for Opinion Target Extraction](https://www.sciencedirect.com/science/article/abs/pii/S0004370218307392). [Artificial Intelligence](http://www.journals.elsevier.com/artificial-intelligence), 268 (2019) 85-95.

If you use **other** IXA pipes tools or just the models, please cite this paper:

+ Rodrigo Agerri, Josu Bermudez and German Rigau (2014): [IXA pipes: Efficient and Ready to Use Multilingual NLP tools](http://www.lrec-conf.org/proceedings/lrec2014/pdf/775_Paper.pdf). In Proceedings of the 9th Language Resources and Evaluation Conference (LREC2014), 26-31 May, 2014, Reykjavik, Iceland.

## Opinion Target Extraction {#ote}

We participated in [Aspect Based Sentiment Analysis task](http://alt.qcri.org/semeval2015/task12/) at [SemeEval 2015](http://alt.qcri.org/semeval2015/), obtaining **best results in the Opinion Target Extraction (OTE) subtask**.

We address the OTE task as a sequence labeling problem. We use the [ixa-pipe-opinion](http://ixa2.si.ehu.es/ixa-pipes) system off-the-shelf to train our OTE models.

+ Software and models: [http://ixa2.si.ehu.es/ixa-pipes](http://ixa2.si.ehu.es/ixa-pipes)

### Citation:

+ Rodrigo Agerri, German Rigau, [Language independent sequence labelling for Opinion Target Extraction](https://www.sciencedirect.com/science/article/abs/pii/S0004370218307392). [Artificial Intelligence](http://www.journals.elsevier.com/artificial-intelligence), 268 (2019) 85-95.

## QWN-PPV: Q-WordNet via Personalized PageRank {#qwn-ppv}

A new Q-WordNet version based on applying Personalized PageRanking to the original Q-WordNet approach. It is a simple, robust and (almost) unsupervised dictionary-based method (Q-WordNet by Personalized PageRanking Vector) to automatically generate polarity lexicons.

The extrinsic evaluations performed show that qwn-ppv outperforms other automatically generated lexicons. It also shows very competitive and robust results with respect to manually annotated ones. Results suggest that no single lexicon is best for every task and dataset and that the intrinsic evaluation of polarity lexicons is not a good indicator of good performance on a Sentiment Analysis task.

Our method is easily applicable to create qwn-ppv(s) other languages, and we demonstrate it by providing polarity lexicons for English and Spanish. The qwn-ppv method allows to easily create quality polarity lexicons whenever no domain-based annotated corpora are available for a given language.

+ Get English and Spanish QWN-PPV lexicons cited in the paper: [http://adimen.si.ehu.es/web/qwn-ppv](http://adimen.si.ehu.es/web/qwn-ppv)
+ Get the software from github: [https://github.com/ixa-ehu/qwn-ppv](https://github.com/ixa-ehu/qwn-ppv)

### Citation:

+ Iñaki San Vicente, Rodrigo Agerri and German Rigau (2014): [Simple, Robust and (almost) Unsupervised Generation of Polarity Lexicons for Multiple Languages](http://aclweb.org/anthology/E/E14/E14-1010.pdf). In Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics (EACL2014), April 26-30, 2014, Gothenburg, Sweden.


