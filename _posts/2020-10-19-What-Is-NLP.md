---
toc: true
layout: post
description: we learn what is NLP and evolution of NLP and some area where you can use NLP.
categories: [NLP]
title: What is NLP, what can we do with NLP?
---
## What is NLP and What can we do with NLP?
Natural language processing (NLP) is a process that the interactions between computers and human language. Which process and analyze large amounts of natural language date. NLP  is a subfield of Linguistics, Computer Science, and Artificial Intelligence.

- Linguistics: Study of language it involves the analysis of language form, language meaning, and language in context.
- Computer Science: Study of algorthimic processes and computational machines.
- Artificial Intelligence: Is intelligence demonstrated by machines, unlike the human and animals.
 
## Evolution of NLP
1. #### Symbolic NLP (1950s - early 1990s):
    Based on complex sets of hand-written rules (like Georgetown experiment 1950s, SHRDLU and ELIZA 1960s, Conceptual ontologies 1970s, HPSG, morphology, semantics 1980s are some of the evolution in NLP)

2. #### Statistical NLP (1990s - 2010s):
    In late 1980s revolution in NLP with the introduction of statistical & machine learning algorthims for language processing.
    
    - *Statistical Methods*:
    In linguistics, a corpus or text corpus is a language resources consisting of a large and structured set of texts. In corpus linguistics, they are used to do statistical analysis and hypothesis testing. Checking occurences or validating linguistics rules within a specific language territory. ML models calls instead for using statistical inference to automatically learn such rules through the analysis of corpora. Drawback of statistical methods is that they require elaborate feature engineering
    
    - *Machine learning algorthimis*:
    With the growth of the web, increasing amounts of raw(unannotated) language data, research has thus increasingly focused on unsupervised and semi-supervised learning algorthimis. The use of word embeddings to capture semantic properties of words, and an increase in end-to-end learning of a higher-level task(e.g question answering) instead of relying on a pipeline od separate intermediate tasks(e.g., part-of-speach tagging and dependency parsing).    
    
3. #### Neural NLP (2010s - present):
    Represntation learning and deep neural network machine learning methods became widespread in NLP. due to a flurry of results showing that such techniques can achieve state-of-the-art results in many natural language tasks.
    
    - *Represntation learning*:
    Feature learning or represntation learning is set of techniques that allows a system to automatically discover the represntation needed for feature detection or classification from raw data.
    
    - *Deep natural network*:
    Neural network is part of a broader family of machine learning methods based on artificial neural network with represntation learning.

### cons in Symbolic NLP:
   - Learning procedures used during ML automatically focus on the most common cases, whereas hand-written rules ofton not at all obvious where the effort should be directed.
   - In ML models that are robust to unfamiliar input and erroneous input. Generally handling such input hand-written rules that make soft decisions, is extermely difficult error-prone and time-consuming.
   - In ML the rules can be made more accurate simply by supplying more input data.However in hand-written rules can only be made more accurate by increasing the complexity of the rules.

### Symbolic methods are still (2020) commonly used
   - When the amount of training data is insufficient to successfully apply machine learning methods. (Apertium system)
   - For preprocessing in NLP pipelines eg., tokenization, or
   - For postprocessing anf transforming the output of NLP pipelines eg., knowledge extraction from syntactic parses.

   1. *Apertium system*: Is a free/open-source rules-based machine translation platfrom.
   2. *Tokenization*: Is the process of converting a sequence of characters into a sequence of tokens.
   3. *Knowledge extraction*: Is the creation of knowledge from structured and unstructured source.

### Common NLP Tasks
   1. Text and speech processing ( OCR, Speech recognition, Speech segmentation, Text-to-speech, Word segmentation).
   2. Morphological analysis (Lemmatization,morphological segmentation, part-of-speech tagging, Stemming).
   3. Syntactic analysis (Grammar induction, sentence breaking, parsing).
   4. Lexical semantic (Lexical semantics, distributional semantics, Named entity recognition NER, Sentiment analysis, Terminology extraction, Word sense disambiguation).
   5. Relational semantics (Relationship extraction, semantic parsing,semantic Role labelling).
   6. Discourse (Coreference resolution, discourse analysis, implicit semantic role labelling, Recognizing textual entailment,Topic segmentation and recognition).
   7. Higher-level NLP applications (automatic summarization, book generation,Dialogue management, Machine translation, Natural language generation NLG, natural language understanding NLU,Question answering).
	
### Resource
 1. Wikipedia [links](https://en.wikipedia.org/wiki/Natural_language_processing#:~:text=Natural%20language%20processing%20(NLP)%20is,amounts%20of%20natural%20language%20data).
 2. fastai about NLP [links](https://github.com/fastai/course-nlp/blob/master/1-what-is-nlp.ipynb).
