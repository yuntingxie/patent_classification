# patent_classification

Using KB-BERT model and generative LLMs to classify Swedish historical patents into DPK classes. For more details and results, please refer to our paper.

This repository contains the jupyter notebook used to fine-tune KB-BERT on patent titles.

## Dataset
Patent data are available at [Swedish Historical Patent Infrastructure](https://svenskahistoriskapatent.se/).
The downloadable dataset will be released soon alongside our forthcoming data paper.

## Prerequisite:
This project requires Python 3.10+ and the following packages:
pandas
numpy
torch
transformers
scikit-learn
tqdm

[Install transformers](https://github.com/ThilinaRajapakse/simpletransformers)

The script is designed to run on an NVIDIA T4 GPU, but it can also be executed on CPU.

## KB-BERT models
We use [Swedish BERT models](https://huggingface.co/KB/bert-base-swedish-cased) trained by Swedish National Library (KB).

## Contact
Yunting Xie (yunting.xie[at]fek.uu.se)
[Uppsala Patent History Group](www.uphg.se)
