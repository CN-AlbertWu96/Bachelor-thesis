# Bachelor-thesis

## Overview of Model

![alt text](https://static.wixstatic.com/media/dafcb6_8690642ad7e74e039d4959217ebcd5b8~mv2.png/v1/fill/w_2285,h_829,al_c,q_90/dafcb6_8690642ad7e74e039d4959217ebcd5b8~mv2.webp "overview")

## Instruction of model

Constructing a hierarchical topic tree is not only a very basic task in corpus analysis, but also plays a key role in information filtering, recommendation systems, and search engines. Existing pattern-based methods classify the organizational components of sentences by extracting contextual semantics. However, by considering each phrase as an independent concept node, the topic proximity and semantic relevance will be more emphasized. 

In this article, we use a TTG (Topic Tree Generator), a multi-level topic-building classification method, in which each node represents a conceptual topic and a cluster of semantically related topics. The classification method uses word vectors and hierarchical clustering to accomplish multi-level topic construction in a recursiveprocess. 

In the recursive process, we have adopted: 

(1) an optimized spherical clustering model thatcan ensure that certain word combinations are shifted downwards when subject clustering is layered to smaller grained topics; 

(2) A local text construction scheme improves the accuracy of the model when stratified to a smaller granularity theme by training word vectors under a smaller granularity of text. And in the experiment section, we mainly utilize the qualitative description and the quantitative description based on the user study to complete the evaluation of the model, and comprehensively consider the accuracy of the relationship between the model results and the term consistency.