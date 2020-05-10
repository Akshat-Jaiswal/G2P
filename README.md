# G2P
Grapheme to Phoneme Convertor

**Problem Statement** : Given an orthographic representation of a word in a language generate it phonemic transcription.


**Intuition** :
The core idea behind this experiment is to apply ideas from neural machine translation to a similar seq2seq prediction task. An input word can be considered as sequence of sub tokens (single or group of characters) which need to be translated into another sequence, namely its phonemic transcript. Phonetic Alphabets are nothing but word in another langauge which makes this problem very similar to machine translation.


**Data Description** : In this implementation we'll be using CMUDict, a publicly available English Pronunciation Dictionary. For more details: http://www.speech.cs.cmu.edu/cgi-bin/cmudict.


**References** :

* The method used in this implementation is described in 
```
Yolchuyeva, Sevinj, Géza Németh, and Bálint Gyires-Tóth. "Transformer based Grapheme-to-Phoneme Conversion." arXiv preprint arXiv:2004.06338 (2020).
```
* Tensorflow Transformer tutorials:
https://www.tensorflow.org/tutorials/text/transformer
