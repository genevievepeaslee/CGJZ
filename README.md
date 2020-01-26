**Deliverable 4**<br>
May 19, 2019

**Group 2**<br>
Claude Zhang<br>
Julia McAnallen<br>
Genevieve Peaslee<br>
Zoe Winkworth<br>

MELDA is a summarization system based on the MEAD system (Radev et al. 2004) with LDA topic modeling incorporated into the content selection step. MELDA can be run by executing `run_all.sh` from inside Multi-Document-Summarizer/src. The default parameters are: 3 topics, 5 sentences per topic; MEAD score weights: 1, 1, 1; Brown Corpus (from NLTK) for IDF score; max threshhold value; and information ordering led by top MEAD score.

For comparison we include two baseline systems - Lead Sentence (hereafter LEAD) and MEAD, which are also run by executing `run_all.sh` from inside CGJZ/src. In order to run MEAD or LEAD, the corresponding lines in `run_all.sh` script must be uncommented. The lines include flags for the version parameters: 'mead' for MEAD and 'lead' for LEAD. (Otherwise, the parameters for MEAD are the same as for MELDA: MEAD score weights: 1, 1, 1; Brown Corpus (from NLTK) for IDF score; max threshhold value; and information ordering led by top MEAD score.)
