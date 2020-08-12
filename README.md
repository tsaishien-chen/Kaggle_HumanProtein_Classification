# Worldwide Kaggle Competition:<br/>Human Protein Atlas Image Classification

Link to challenge website: https://www.kaggle.com/c/human-protein-atlas-image-classification/overview

To clone this repo, please execute:
```
git clone https://github.com/tsaishien-chen/Human_Protein_Classification.git
```

## Requirements
* Python 3.5 or newer:  
  Run `pip3 install -r requirements.txt` to install all dependence packages.

## Reproduce

1. Download the dataset (save all training images into `src/total_train/` and all testing images into `src/test/`).

2. Execute:
```
bash src/Pytorch/test.sh [directory of sample_submission.csv]
```

3. The final result will show up here: `src/Pytorch/submit/result.csv`.
