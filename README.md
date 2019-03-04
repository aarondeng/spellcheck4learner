# A spellcheck tool for data preprocessing in constructing large scale learner English corpora 
## Data for Evaluation
See file: gold500.txt,https://github.com/aarondeng/spellcheck4learner/blob/master/gold500.txt
### data source
The Evaluation Data retrieved from the corpus TECCL V1.1 (http://corpus.bfsu.edu.cn/content/teccl-corpus). We used only the first 500 articles（with file names ranging from  TECCL00001 to TECCL00507），totalling about 11,300 words，to mannually annotate 589 places of non-word spelling errors.
### data structure
The gold500.txt file contains a header including columns: wrong, correct, idx, sentence, file name. The column of wrong contains the misspelled word, that of correct provides the mannually corrected word, while the column of idx stores the zero-based index of the position of the wrong word in the sentence. The columns of sentence and file name are obvious as what they suggest to be.
