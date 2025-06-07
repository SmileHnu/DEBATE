# DEBATE: A Dataset for Disentangling Textual Ambiguity in Mandarin Through Speech
[![arXiv](https://img.shields.io/badge/Arxiv-paper-blue)]  [![GitHub](https://img.shields.io/badge/GitHub-Repo-green)](https://github.com/SmileHnu/DEBATE) [![Zenodo](https://img.shields.io/badge/Zenodo-dataset-yellow)](https://zenodo.org/records/15609922)

This is the official repository of the DEBATE dataset, containing detailed information related to the dataset.
<div align="center"><img width="600px" src="figure/overview.png" /></div>

## DEBATE Overview

DEBATE dataset is a unique public Chinese speech-text dataset designed to study how speech cues and patterns—pronunciation, pause, stress and intonation—can help resolve textual ambiguity and reveal a speaker’s true intent.It contains 1,001 carefully selected ambiguous utterances, each recorded by 10 native speakers. 

The table below provides the detailed statistics of the DEBATE dataset.
|   Tasks  | Samples | Hours | Mean Duration(s) | Duration Range(s) |
|:--------:|:-------:|:-----:|:----------------:|:-----------------:|
|Task_Proun| 2000    |1.64   |2.94              |1.15-5.80          |
|Task_Pause| 4010    |4.28   |3.84              |1.60-11.80         |
|Task_Stres| 4000    |3.74   |3.37              |1.43-8.51          |
|**Total** |**10010**|**9.66**|**3.47**         |**1.15-11.80**     |

## Dataset Construct
<div align="center"><img width="600px" src="figure/pipeline.png" /></div>
The data was collected from three primary sources:<br>
&bull; open-source corpora<br>
&bull; social media platforms<br>
&bull; standardised examination question banks

