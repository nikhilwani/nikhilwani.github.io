---
layout: page
title: Research
permalink: /research/
---

<style>
body
{
	text-align: justify;
}

</style>

<!-- I am broadly interested in Machine Learning and Natural Language Processing.

My work focuses on the intersection.(chip)
AI with NLP + HCI: Some directions.

Project Format: Stanford Reinforcement Learning.
Poster Format:  Use Latex, See Stanford Posters.
Presentation Format: Beamer. -->

---
__Hindi to English Hybrid Machine Translation System for Judical Domain__  
[[paper]]() [[poster]]()  
Advisor: Dr Pushpak Bhattacharya | Factor Based MT,NMT| Govt. of India and IIT Bombay  


<!-- Tutorial - http://www.cfilt.iitb.ac.in/resources/surveys/NMT-survey-paper.pdf

Dataset: IITB Parallel Corpus. WAT Shared Task. (75K lakh, hindi-english sentences)  
Evaluation Metrics: BLUE

Approaches:  
1.Factor-based SMT systems, where factors are WSD, etc etc  
Moses 

2.NMT - Encoder-Decoder model


Exploration of Hiden Markov Models, Conditional Random Fields for the problem of sequence <something>. I plan to complete this as a course project with Prof. Sunita Sarawagi during her Graphical Modeling in Spring 19.
Two stages. First stage - NAACL Shared Task. Second we backpropagate the output of the ensembled classifiers. 
Leverage Cognitive NLP. Experiments in Ensemble modeling with Neural Network. Princeton's Wordnet, StanfordCore NLP for , CMU's for vowels. Eye Tracking machine. This project was our submission to NLP-BEA Workshop at NAACL 2018. Lexical semantics (https://www.wikiwand.com/en/Lexical_semantics). We then incorporate Named Entity Recognition, Parts of Speech Tagger. Human Gaze features with Eye tracking experiments. We show a correlation between cognitive features and textual features. -->

•  The aim is to attempt to build the first ever large-scale translation system of complete judgments in Indian languages for eventual publication in English. Working on three approaches: Phrasal Factor-based Statistical Machine Translation(SMT), Phrasal Example-based SMT, and Encoder-Decoder Neural Machine Translation(NMT) Architecture.  
• Experimenting with Fine-tuning and domain adaptation of NE tagging, (stochastic)PoS tagging, WSD and NE Transliteration, which are being used as factors for FSMT model for the Judicial domain system. Existing tools support for Indian Languages is available only for healthcare and tourism domain.  
 • Working on design of verb-based templates with VerbNet for Hindi text on the EBMT model. Surveyed and implemented baseline Encoder-Decoder models in PyTorch on a subset of the IIT Bombay parallel corpus(Hindi to English) of 75K sentences.  
 •  Developing a Flask-based python web tool to implement a web-based version of the system.  

<!-- ---
__Effective Voting Ensemble models for Contextually Complex Word Identification__ ***[(NAACL 18 Shared Task)](https://sites.google.com/view/cwisharedtask2018)***  
[[paper]]() [[poster]]()  
Advisors: Dr. Pushpak Bhattacharya and Dr. Abhijeet Mishra (IBM Research) | Machine Learning, NLP| CSE, IIT Bombay  

We achieve State-of-the art on three datasets. Our model is 1.5x better than the best submitted model.
1. Voting Ensemble Appoach.
Stacked with 
First stage - NAACL Shared Task. Second we backpropagate the output of the ensembled classifiers. 
Leverage Cognitive NLP. Experiments in Ensemble modeling with Neural Network. Princeton's Wordnet, StanfordCore NLP for , CMU's for vowels. Eye Tracking machine. This project was our submission to NLP-BEA Workshop at NAACL 2018. Lexical semantics (https://www.wikiwand.com/en/Lexical_semantics). We then incorporate Named Entity Recognition, Parts of Speech Tagger. Human Gaze features with Eye tracking experiments. We show a correlation between cognitive features and textual features.
Two stages.

2. Cognitive NLP Approach.  
Physcolinguistic features. Dataset annotation. Experiment setup - user study approcahes borrowed from HCI.
Terminology
http://www.cfilt.iitb.ac.in/resources/surveys/eye-tracking-nivvedan-may14.pdf

3. Deep Learning Approach.  
End-to-End model 

--- -->
---
__Automatic Contextually Complex Word Identification System__  
Advisor: Dr Pushpak Bhattacharya | Factor Based MT,NMT| Govt. of India and IIT Bombay 

 •  The goal is to detect challenging words or phrases in a given context of the sentence for non-native English speakers. Achieved state-of-the-art classification system with a highest F1 score of  0.91 , outperforming the current score of 0.84 as well as the best F1 score across all 6 available English monolingual CWI datasets from both SemEval‘16 and NAACL‘18 shared tasks.  
 •  Worked on  Ensemble models with GloVe Embedding based Hard Voter , and feed forward NN based Voter using KL-divergence loss function . Experimented with 16 classifiers, out of which 8 best Tree-based classifiers were implemented for Ensembling. Outperformed 11 rule-based baselines and it falls within 0.042 to 0.026% of the best model’s score. Harnessed WordNet  features, which revealed higher degree of Polysemy and deeper Hyponym and Hypernym tree depth for complex words.  
 •  Developed  Cognitively-driven Ensemble model. Designed experiments with  SSR-Research Eyelink-1000 Plus eyetracker to generate embeddings from non-native English speakers’ eye movements. Utilized Eye-Gaze and  MRC Psycholinguistic Database based features and showed that complex words have higher abstractness, fixation count, and saccade movement. Incorporated the features of the previous model and equaled the best system’s F1 score of  0.84.  
 •  Designed, implemented (in Keras), and analyzed  end-to-end multi-channel CNN architecture,  which  uses multiple scale embedding representation for each of the three channels: char-level contextual(ELMo), word-level (GloVe), and learnt representation of the features in previous stated models along with cognitive-embeddings, POS and NER tags to achieve the current state-of-the-art F1 score of 0.91.  

---
__Probablistic Models for Intelligent Text Input Processing__ 
[[paper]]() [[report]]()  
Advisor: Dr. Anirudha Joshi | Machine Learning, Human Computer Interaction (HCI) (Computational Interaction) | IDC, IIT Bombay <br>

<!-- 
In this Thesis, we tackle 3 tasks.

1. 
 Probablistic Modeling of Indic Keyboard Swarachakra for improved touch accuracy -->
<!-- We address the problem of fat finger touch X as a multi-class classification. We build a text-input tool 
This project was part of my internship at IIT Bombay. Android text input tool to get the touches.  -->

<!-- 2. 
Probabilistic Decoding for Intelligent Text Entry
 -->

 •  Built a  touch Keyboard model which extends to a Probabilistic model, and is functionally independent of any Language model for the  Swarachakra app - an Indic touch keyboard. Worked on solving the problem of “fat finger touch”, where the target touch is at the boundary intersection of the adjacent keys and equidistant from the center of the keys.  
 •  Proposed the notion of  touch as a Machine Learning problem , specifically by modeling each key as a class label for touch classification task. Experimented with Geometric probability distributions and different shapes which generated internal non-rectangular key boundaries. Showed a reduction in the total touch error rate by  7.47% against the Non Probabilistic model and  1.15%-3.15%  against the baseline Swarachakra model.  
 •  Developed an Android text input tool to analyze the distribution of touches over each keys. Designed experimented bi-grams that utilized the 8 angles of touch approaches and 3 hand postures. Obtained the posterior distribution over each key.  
 •  Learned using 18,240 recorded touch inputs for which it used a Naive Bayes classifier and assigned an adapted probability distribution to each of the 39 class labels.


---
__Neural Language Models for Intelligent Text Input Prediction__  
[[paper]]() [[report]]()  
Advisor: Advisor:  Dr. Anirudha Joshi and Dr. Pushpak Bhattacharyya| Machine Learning, Human Computer Interaction (HCI) (Computational Interaction) | IDC, IIT Bombay <br>


<!-- 1. SRILM. We build 3 n-gram models. on Hindi, MArathi.

2. Use develop LSTM with framing logic as character, word and sub-word based.

3. We experiment with Loss functions and optimization 

Help 

https://web.stanford.edu/class/cs124/lec/languagemodeling.pdf

https://stats.stackexchange.com/questions/10302/what-is-perplexity
https://www.google.com/search?q=Language+modeling+Preethy+jyothu&oq=Language+modeling+Preethy+jyothu&aqs=chrome..69i57.10798j0j1&sourceid=chrome&ie=UTF-8
https://github.com/wojzaremba/lstm/tree/master/data
https://arxiv.org/pdf/1409.2329.pdf
http://www.fit.vutbr.cz/~imikolov/rnnlm/thesis.pdf
https://srilm-python.readthedocs.io/en/latest/

IMP
http://idiom.ucsd.edu/~rlevy/teaching/2015winter/lign165/lectures/lecture13/lecture13_ngrams_with_SRILM.pdf
https://cmusphinx.github.io/wiki/tutoriallm/
http://ojs.pythonpapers.org/index.php/tpp/article/view/82/83
https://openreview.net/forum?id=HkwZSG-CZ
http://www.speech.sri.com/projects/srilm/papers/icslp2002-srilm.pdf
https://stackoverflow.com/questions/50018674/how-to-use-srilm-to-build-a-language-model

---

 -->
 •  Implemented (in TensorFlow) and matched the results of popular language modelling baselines (with PTB).  
 •  Worked on and designed Neural Language models which were framed at the character, sub-word, and word level for English and two Indian Languages(Hindi and Marathi) for Swarachakra Keyboard’s text prediction feature.  
 •  Experimenting further by leveraging  SRILM based n-gram statistics. Achieved a baseline perplexity score of 132.27 on the English Swarachakra frequency corpus.  
 • Working on a new evaluation technique which ensembles human-in-loop empirical and computational evaluation techniques.  

<!-- __A study of all bidirectional LSTM models for Neural Machine Comprehension__  
[[paper]]() [[poster]]()  
Self Project| Deep Learning, Natural Language Understanding| CS, IIT Bombay  

Find a problem which can be solved using sequences.
Exploration of Hiden Markov Models, Conditional Random Fields for the problem of sequence <something>. I plan to complete this as a course project with Prof. Sunita Sarawagi during her Graphical Modeling in Spring 19. Active attension like active reading. Anticipate what will come next
Two stages. 

How can the act of anticipation be modeled? Inbox text prediction

Text generation and then selection 

First stage - NAACL Shared Task. Second we backpropagate the output of the ensembled classifiers. 
Leverage Cognitive NLP. Experiments in Ensemble modeling with Neural Network. Princeton's Wordnet, StanfordCore NLP for , CMU's for vowels. Eye Tracking machine. This project was our submission to NLP-BEA Workshop at NAACL 2018. Lexical semantics (https://www.wikiwand.com/en/Lexical_semantics). We then incorporate Named Entity Recognition, Parts of Speech Tagger. Human Gaze features with Eye tracking experiments. We show a correlation between cognitive features and textual features.

A comparative study of all bidirectional attension based LSTM models for Neural Machine Comprehension -->

---
__Efficient Multi-Scale 3D Convolutional Neural Network for Image Segmentation__  
[[paper]]() [[poster]]()  
Advisor: C.P. Mammen | Deep Learning, Vision| Nvidia Internship  

 •  Developed and deployed a multi-scale 3D Convolutional NN coupled with post-processing on a 3D fully connected Conditional Random Field to detect and segment challenging brain lesion structures on the multi-modal  BRATS 17  MRI dataset.  
 •  Proposed and experimented with operationalizing the processing of NIFTI formatted images parallely at multiple scales by two parallel convolutional pathways: one to leverage the utilization of small kernels and the other for faster computation of 3d images.  •  Achieved a mean DICE score of  68.6 , and  0.3x times  faster training time on Nvidia Quadro M6000 and Titan X.  
 •  Implemented (in Theano) and matched the results of state-of-the-art lesion segmentation system ( DeepMedic ). Implemented (in Caffe) a Nvidia DIGITS image segmentation module. Wrote scripts using  C3D library and preprocessing scripts and post-processing scripts using  MITK Workbench .  

---
__Is your Statement Purposeless? Predicting Computer Science Graduate School Admission Acceptance based on Statement of Purpose__  
Advisor: Prof. Pusphak Bhattacharya  
 •  Proposed and developed a  prophecy system that aids prospective applicants with a pure SOP based acceptance forecast of their application. The goal was to mitigate the  problem of unpredictability of CS Graduate School Admissions . Established the feasibility of such a system by demonstrating a baseline F1 score of  0.83  on a toy dataset of 50 full-length SOPs.  
 •  Explored classification with limited data techniques and experimented with  Few-shot learning, Transfer Learning, and Metric Learning.  Optimized the classic  SVM classifier with RBF kernel to achieve  0.92 over the acceptance class. Created a toy dataset from scratch and proposed first ever such dataset. Conducted  Ablation tests on feature sets using multi-fold cross-validation and  feature significance test  by ranking them from highest to lowest based on  Information Gain.  
 •  Showed that Word Embedding based features and Document Similarity based features outperform other identified feature combination for this task. Identified and accounted for real life factors that may affect admission decisions such as ease of readability using Flesch score, coreference distance between mentions, sentence structure variation, count of discourse connectors and named entities of professors, number of errors.  
 •  Developed a light document similarity  Python package  to support reproducibility of identified similarity based features.  

<!-- 
Version 1 - Setting Baseline results, Document Similarity measures  
exploit document similarity.
[[baseline paper]](https://cdn.iiit.ac.in/cdn/ltrc.iiit.ac.in/icon2017/proceedings/icon2017/pdf/W17-7518.pdf){:target="_blank"} [[slides]]()  
desultory SOPs- rambling, filled with 
Questioning Does god play dice, lead me to think - [Does the admissions  commite also play dice?](http://www.hawking.org.uk/does-god-play-dice.html) What attributes does an candidate at the top university have? 
Answers to these questions led to find features for this supervised learning problem. This problem clears deals with **classification with limited training data**. We set an initial baseline accuracy using Machine learning models. **Document similarity** . Structural similarity. 

Version 2 - Deep Learning techiques for classification with limited data  
[[report]]()  
While the probability of acceptance is non-trival, the rejection case is rather simpler. We are exploring Deep Learing techniques for classification with limited data. Few Shot learning for accept class, non availablity of dataset - expansion of dataset.
Reverese the problem and you'd have Rejection is simple. Expatiating,  -->


---

<!-- 
# **Research Implementations** - Deep Semantics

https://www.wikiwand.com/en/Natural_language_processing
* Neural Machine Translation (Keras Implementation)
* Nerual NER (TensorFlow Implementation)
* Reinforcement Learning for NLP
* NLP from scrath. 

 -->
# **Datasets**
Application of HCI principals were used to design the experiment these mini datasets for learning. User study research incorporates counterbalancing, 
latin square matrix and other user study methodology.

**Large**
1. Eye tracking annotated  Wikipedia Dataset  
Eye Tracking Machine. 

* ``English`` (v 1.0) (v 2.0) 
<br>Complimentary - Amazon Mtruk Crowdsourced.

**Small (Pilot Datasets)** `` N < 5000 ``  
Version 1.0
2. Indian Newspapers Visualisation Metadata
[stats] [[kaggle]](https://www.kaggle.com/nikhilwani/regional-newspaper-visualisation-metadata)

3. Stress Detection from Smartphone Keyboard  
Prof. Ahamad's Keyboard Tool | ACM Summer School Project





