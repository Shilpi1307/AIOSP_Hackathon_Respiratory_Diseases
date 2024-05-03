# AIOSP_Hackathon_Respiratory_Diseases

# Problem Statement(s)
Segment the respiratory cycles from the audio files respectively and annotate accordingly<br>
Then build two models:<br>
a model to classify respiratory diseases, i.e., COPD, LRTI, URTI<br>
a model to detect whether a recording contains crackles, wheezes, both or none<br>

# Explaining models:
**Inputs:**<br>
The Respiratory Sound Database: includes 920 annotated recordings of varying length - 10s to 90s taken from 126 patients.
The split of the 920 recordings is as follows:<br>
Training: 80%<br>
Validation: 10% <br>
Test: 10%<br>
The models have been trained on 724 .wav sound files and annotation .txt files

**Outputs:**<br>
The model to classify respiratory diseases classifies them into COPD, LRTI, or URTI<br>
The model to detect crackles, wheezes gives the output on the basis of the following encoding of classes:<br>
0: None<br>
1: Crackles only<br>
2: Wheezes only<br>
3: Both<br>
