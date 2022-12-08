# Introduction
Syntactic parsing is an important task in natural language processing that aims to uncover the syntactic structure (e.g., a constituent or dependency tree) of an input sentence. Such syntactic structures have been found useful in downstream tasks such as semantic parsing, relation extraction, and machine translation.

Supervised learning is the main technique used to automatically learn a syntactic parser from data. It requires the training sentences to be manually annotated with their correct parse trees. A major challenge faced by supervised parsing is that syntactically annotated sentences are not always available for a target language or domain and building a high-quality annotated corpus is very expensive and time-consuming.

A radical solution to this challenge is **unsupervised parsing**, sometimes also called **grammar induction**, which learns a parser from training sentences without parse tree annotations. Unsupervised parsing can also serve as the basis for semi-supervised and transfer learning of syntactic parsers when there exist both unannotated sentences and (in-domain or out-of-domain) annotated sentences. In addition, the research of unsupervised parsing is deemed interesting in the field of machine learning because it is a representative task of unsupervised structured prediction, and in the field of cognitive science because it inspires and verifies cognitive research of human language acquisition.

The research on unsupervised parsing has a long history, dating back to theoretical studies in 1960s and algorithmic and empirical studies in 1970s. Although deemed an interesting topic by the NLP community, unsupervised parsing had received much less attention than supervised parsing over the past few decades. 

More recently, however, there has been a resurgence of interest in unsupervised parsing, with more than ten papers on unsupervised parsing published in top NLP and AI venues over the past two years, including a best paper at ICLR 2019, a best paper nominee at ACL 2019, and a best paper nominee at EMNLP 2020.
This renewed interest in unsupervised parsing can be attributed to the combination of two recent trends. First, there is a general trend in deep learning towards unsupervised training or pre-training. Second, there is an emerging trend in the NLP community towards finding or modeling linguistic structures in neural models. The research on unsupervised parsing fits these two trends perfectly.

Because of the renewed attention on unsupervised parsing and its relevance to the recent trends in the NLP community, we believe a book on unsupervised parsing can be timely and beneficial to many *ACL conference attendees. 
The book will introduce to the general audience what unsupervised parsing does and how it can be useful for and beyond syntactic parsing. It will then provide a systematic overview of major classes of approaches to unsupervised parsing, namely generative and discriminative approaches, and analyze their relative strengths and weaknesses. It will cover both decade-old statistical approaches and more recent neural approaches to give the audience a sense of the historical and recent development of the field. We also plan to discuss emerging research topics such as BERT-based approaches and visually grounded learning.

We expect that by taking this book, one can not only obtain a deep understanding of the literature and methodology of unsupervised parsing and become well prepared for his own research into unsupervised parsing, but may also get inspirations from the ideas and techniques of unsupervised parsing and apply or extend them to other NLP tasks that can potentially benefit from implicitly learned linguistic structures.