# LRL-NMT

This repo contains code pertaining to the BSc thesis:

### Towards Improving Neural Machine Translation Systems for Lower-Resourced Languages:
#### Optimising Preprocessing and Data Augmentation Techniques for English to Irish Translation

##### Joshua Wolfe Brook, Amsterdam University College

This research aims to improve upon automatic language translation systems for LRLs through optimising the data preprocessing pipeline and artificially increasing the size of the training dataset through algorithmic data augmentation techniques. 
The English - Irish language pair is chosen and used as a case study to determine the effectiveness of the proposed approach, due to the author's familiarity with it and the fact that it should pose a suitable challenge for LRL-based NMT.
The proposed system creates an augmentation process which involves targeted word replacement based on POS tags, contextual similarity, and semantic relationships. 
The newly-generated data is concatenated with existing datasets, and used to train multiple versions of a Transformer-based NMT model, in order to compare how training on different datasets can affect translation quality. 
Both quantitative and qualitative results demonstrate that the preprocessing pipeline and the data augmentation approach improve NMT performance, as evidenced by increased automatic evaluation scores and perceived translation accuracy.
These findings highlight the potential of data-based approaches as valuable techniques to enhance NMT systems and address limitations caused by a lack of training data.
