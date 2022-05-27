# Linguistic Background in Speech Recognition
### Codeswitching research
### [Paper](https://github.com/DariaRev/CodeSwitching_SpeechRecognition_mistakes/files/8786741/_._._all2.pdf)


This research aims to investigate mistakes that speech recognition models make when trying to interpret codeswitching. The repository provides [code for parsing data](https://colab.research.google.com/drive/1EucXi0fVu9fmU-8wshE9zX602lMrtgdo?usp=sharing), [part of data from synthesizing](https://drive.google.com/drive/folders/1-3iuYHO0m1BjzIiG8hByGnxMJVe-Z6Yr?usp=sharing), [alignment and analysis](https://colab.research.google.com/drive/1tgkUkdIbZrmLKnzazf8jqVqPj31XWCGf?usp=sharing).

## What it is about?
In this article we consider that people who use code switching are not only bilinguals. Since we want to focus on Russian-speaking community, we are going to explore code-switching in terms of its application in Russia. 

We need to keep in mind is that codeswitching **can be different**. There are two types of codeswitching that people use - intersententional (between sentences) and intrasententional (inside one sentence). It is still a big problem to recognize it when it is inside a sentence. Here we try to understand how well computer can recognize code switching, especially intrasententional and what mistakes it makes.

As a result, we show different groups of mistakes, that are made in speech recognition and alignment process. We use CER and WER in order to find how well our words and sentences are recognized. Moreover, we suggest an aproach to make this recognition better and CER lower. We use IPA for all words, also we have added CER specialy for words in IPA. Farther, we concatenate those words in true sentences which refer to the same utterance in predicted sentences.
It helps us to lower CER a bit (difference is 3%). 

So, for further work there are plenty of things that can be automatically or manually done to avoid some mistakes and to make CER better. It contains processing of numbers, hangling of things like one-two letter words and reverse method of that we use here. 


