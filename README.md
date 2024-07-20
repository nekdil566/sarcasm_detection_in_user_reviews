# sarcasm_detection_in_user_reviews
# Overview
This package contains the data and code necessary to replicate the experiments conducted in the study of sarcasm detection in text data. It includes two main experiments: binary classification and multiclassification of sarcasm.

# Directory Structure
# Data Files:
- Sarcasm_multiclassification.csv: Dataset used for multiclass sarcasm detection.
- annotated_comments_binary.csv: Dataset used for binary sarcasm detection.

# Code Files:
- Multi Classification sarcasm detection python code (DL algorithms):
  - GRU, BiGRU, CNN_for_multiclassification_sarcasm.ipynb: Jupyter notebook for multiclass sarcasm detection using GRU, BiGRU, and CNN models.
  - LSTM, BILSTM_Multi_classification_sarcasm.ipynb: Jupyter notebook for multiclass sarcasm detection using LSTM and BiLSTM models.
  - RNN_BiRNN_MultiClassification_sarcasm_Dataset.ipynb: Jupyter notebook for multiclass sarcasm detection using RNN and BiRNN models.
- binary classification updated: Folder containing updated notebooks for binary classification (specific notebooks to be listed).

# Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: pandas, numpy, scikit-learn, keras, tensorflow

# Running the Experiments
## Binary Classification:
1. Open annotated_comments_binary.csv for data overview.
2. Run notebooks inside the binary classification updated folder (specific notebooks to be listed).

## Multiclass Classification:
1. Open Sarcasm_multiclassification.csv for data overview.
2. Choose and run one of the following notebooks based on the desired model:
   - GRU, BiGRU, CNN_for_multiclassification_sarcasm.ipynb
   - LSTM, BILSTM_Multi_classification_sarcasm.ipynb
   - RNN_BiRNN_MultiClassification_sarcasm_Dataset.ipynb

# Data Description
- Sarcasm_multiclassification.csv contains multiple labels per comment for sarcasm detection.
- annotated_comments_binary.csv contains binary labels (sarcasm or not) per comment.

# Contact Information
- For questions or feedback regarding the replication package, please contact [naikdil2002@gmail.com].
