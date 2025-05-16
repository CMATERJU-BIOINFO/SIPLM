# SIPLM (Self-Interacting Protein Language Model)

This repository contains code and resources for the SIPLM project, which focuses on protein sequence analysis using BERT-based models.

## Project Structure

- 1_Data_curation.ipynb: Data preparation and curation notebook
- 2_Finetuned_Model.ipynb: Model fine-tuning notebook
- 3_Seq_level_pred.ipynb: Sequence-level prediction notebook
- Dataset/: Contains training and testing datasets
- Result/: Model results and evaluations
- proteinbert-with-pretrain-model/: Pre-trained model files

## Large Files Note
The pre-trained model file epoch_92400_sample_23500000.pkl (>100MB) is not included in this repository due to GitHub's file size limitations. Please contact the repository owners for access to the model file.

## Setup and Installation
1. Clone this repository
2. Download the model file separately and place it in the proteinbert-with-pretrain-model/ directory
3. Install the required Python packages (provided in the notebooks)
