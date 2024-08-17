This repository contains code for the master's thesis "Fine-tuning Whisper for Afrikaans" by Sebastiaan Peeters for the Master Digital Text Analysis 2023-2024 at the University of Antwerp.
If you are not the supervisor or assessor of the thesis, this code will likely be of no interest to you. After the evaluation period, this repository will become private.

Note that the code in this repository won't run unless you also download the corpora and place them in the correct folders and/or fine-tune the models. 
Given the large size of both the models and corpora, they were not uploaded here.


The code in this repository is organized in four folders:

* corpus processing: contains the python notebooks used for extracting data from the NCHLT Afrikaans corpus and the Corpus Gesproken Nederlands.

* fine-tuning: contains the actual code for fine-tuning the models. A separate notebook was created for each model, but most of the code is copy pasted from one notebook to the next.

* model evaluation: contains the code used for evaluating the fine-tuned models on each of the three test sets used. 

* Visualizations: contains the code used for generating the plots and tables used in the thesis.
