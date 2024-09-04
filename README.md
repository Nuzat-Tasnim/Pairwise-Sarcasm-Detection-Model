# Pairwise Learning Approach Using Siamese Neural Network for Contextual Sarcasm Detection

This repository contains the Python code for the paper titled **"Pairwise Learning Approach Using Siamese Neural Network for Contextual Sarcasm Detection"**, published at the ICCIT 2023 conference. The paper is available on the [ITEE website](https://ieeexplore.ieee.org/document/10441610).

## Overview

The project focuses on sarcasm detection using a pairwise learning approach. The model employs a variant of the Siamese neural network to process conversation-response pairs. Key components include:

- **Data Preprocessing**: Text data is preprocessed using the Python spaCy package.
- **Feature Extraction**: Pre-trained BERT-Large is used to extract features from input pairs.
- **Model Architecture**: The Siamese network processes the target text and its context separately through LSTM layers. The intermediate outputs are concatenated and further processed by multi-layer LSTM and hidden layers to classify the text as sarcastic or non-sarcastic.

## Dataset

The dataset for this work was collected from the shared task of the Codalab (2020) Sarcasm Detection Task. You can access the dataset [here](https://competitions.codalab.org/competitions/22247).

## Results

Experimental evaluation on Twitter and Reddit datasets yielded notable F1-scores of 0.73 and 0.66, respectively.

## Citation

If you use this code, please cite:

```bibtex
@INPROCEEDINGS{10441610,
  author={Tasnim, Nuzat and Sultana, Nasrin},
  booktitle={2023 26th International Conference on Computer and Information Technology (ICCIT)}, 
  title={Pairwise Learning Approach Using Siamese Neural Network For Contextual Sarcasm Detection}, 
  year={2023},
  volume={},
  number={},
  pages={1-6},
  keywords={Social networking (online);Blogs;Neural networks;Feature extraction;Market research;Natural language processing;Information technology;microblogging;pairwise learning;siamese neural network},
  doi={10.1109/ICCIT60459.2023.10441610}}
