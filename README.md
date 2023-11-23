# BERT-NMT

Code for the BSc thesis:

"Towards Improving Neural Machine Translation Systems for Lower-Resourced Languages:
Optimising Preprocessing and Data Augmentation Techniques for English to Irish Translation"

Neural Machine Translation (NMT) systems have recently achieved significant advancements in the quality and availability of automatically translated text. However, the lack of readily-available high-quality parallel training data poses a challenge to the robustness and generalisation capabilities of NMT models trained to translate Lower-Resourced Languages (LRLs).
This research aims to improve upon these automatic language translation systems, specifically for LRLs, through optimising the data preprocessing pipeline and artificially increasing the size of the training dataset through algorithmic data augmentation techniques. 
The English - Irish language pair is chosen and used as a case study to determine the effectiveness of the proposed approach, due to the author's familiarity with it and the fact that it should pose a suitable challenge for LRL-based NMT.
The proposed system combines various NLP techniques and models, creating an augmentation process which involves targeted word replacement based on POS tags, contextual similarity, and semantic relationships. 
The newly-generated data is concatenated with the existing data, and used to train multiple versions of a Transformer-based NMT model, in order to compare how training on different datasets can affect translation quality. 
Both quantitative and qualitative results demonstrate that the preprocessing pipeline and the data augmentation approach improve NMT performance, as evidenced by increased automatic evaluation scores and perceived translation accuracy.
These findings highlight the potential of data-based approaches as valuable techniques to enhance NMT systems and address limitations caused by a lack of training data.