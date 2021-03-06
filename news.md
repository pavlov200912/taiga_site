### 22/02/2019 - ULMFit on Taiga available

Universal language model for Russian -  [see on github](https://github.com/mamamot/Russian-ULMFit/)!

---


### 10/11/2018 - Corpus Download now open!

Taiga corpus is now open for [downloading](https://tatianashavrina.github.io/taiga_site/downloads)!

---


### 09/11/2018 - Vector Model Release

[Spark in me](http://spark-in.me) releases a Fasttext model, trained on random mix of Russian Wikipedia, Taiga and Common Crawl

[Download link](https://goo.gl/g6HmLU)

Params
Standard params - (3,6) n-grams + vector dimensionality is 300.

Usage:
```
import fastText as ft
ft_model_big = ft.load_model('model')
```
And then just refer to
https://github.com/facebookresearch/fastText/blob/master/python/fastText/FastText.py


---

### 14/08/2018 - Corpus update - Fake news dataset
We have added fake news dataset in our corpus collection: 150k tokens from  panorama.pub (Russian fake news site, analogous to Onion) - tagged and added to "News" segment.

Other news sources can be considered a "reliable news" class in case of binary classification task.

---


### 20/06/2018 - Vector Model Release
Thanks to [Andrey Kutuzov](http://rusvectores.org/ru/contacts/) -  a skipgram model for Taiga is now available at [RusVectores project page](http://rusvectores.org/ru/models/)

On RusVectores page you can also find online semantic similarity calculator on different models, including Taiga

---


### 21/04/2018 - Taiga on Universal Dependencies site
Taiga subcorpus with manual annotation is now presented on [universaldependencies.org](http://universaldependencies.org/) (Russian)
 - training: 50% (10K tokens, 880 sentences)
 - test: 50% (10K tokens, 884 sentences)
 
Subcorpus [repository](https://github.com/UniversalDependencies/UD_Russian-Taiga/tree/master)

All credits go to [Olga Lyashevskaya](https://www.hse.ru/staff/olesar) and students

---

