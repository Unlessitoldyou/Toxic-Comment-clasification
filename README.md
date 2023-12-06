# Toxic-Comment-clasification

PROJECT TITLE: 
Wikipedia Toxic Comments Classification

PROJECT DESCRIPTION: 
With the rise of cyber-bullying and online harassment, addressing toxicity in user-generated content has become a critical challenge in public online communities. This paper focuses on utilizing Wikipedia's Toxic Comment as training data to develop binary and multi-label classifiers that are capable of detecting various forms of toxicity in online discussions. The solution includes four models: a Bidirectional LSTM and BERT model for binary classification of toxic and non-toxic comments, and a BERT model and Bidirectional LSTM for multilabel classification of different types of toxicity.

HOW TO INSTALL AND RUN THE PROJECT:
1. Download the .ipynb file
2. Put in location on file finder
3. Create data subfolder and place models into it
4. Establish a path to your personal file (this is different than the paths in the notebook)
4. Run notebook (relative paths should automatically update)

RELEVANT RESOURCE:
The initial paper that spurred this research is a good resource to use.

Nagwa El-Makky Mai Ibrahim Marwan Torki. “Imbalanced Toxic Comments Classification using Data Augmentation and Deep Learning”. In: IEEE (2018).
https://ieeexplore.ieee.org/document/8614166

GITHUB:
https://github.com/soyesiku/Toxic-Comments-Classification-using-Deep-Learning-Techniques


ROADMAP OF FUTURE ENDEAVORS:
Much work needs to be done in order to improve the work done in this project. Here are the key steps:
1. Successfully find and solve memory leak issue in training loops
2. Run BERT models (now that memory leak has been addressed)
3. Run Bi-LSTM models (binary and multi-label) for more than 2 epochs


AUTHORS:
Seyi Oyesiku
