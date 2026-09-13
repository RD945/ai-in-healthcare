# AI in Healthcare

Jupyter notebooks exploring machine learning and data analysis workflows for healthcare data.

## Labs

- `Lab1_AI_in_Healthcare.ipynb`: UCI heart disease classification, ECG data from MIT-BIH, and an image-data demonstration.
- `LAB2_AI_in_Healthcare.ipynb`: Exploratory analysis and preprocessing of the UCI heart failure clinical records dataset.
- `LAB3_AI_in_Healthcare.ipynb`: Multimodal preprocessing using tabular diabetes data, medical text, chest X-ray images, and ECG signals.
- `LAB4_AI_in_Healthcare.ipynb`: Breast cancer classification with feature scaling, logistic regression, and evaluation metrics.

## Setup

Install Python 3 and the notebook dependencies:

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn scikit-learn scipy wfdb ucimlrepo opencv-python pillow
```

Launch Jupyter from the repository directory:

```bash
jupyter notebook
```

Open a notebook and run its cells in order. Several notebooks download datasets from online sources, so an internet connection may be required.

## Local Data

`LAB3_AI_in_Healthcare.ipynb` expects these files in the notebook's working directory:

- `diabetes.csv`
- `mtsamples.csv`
- `chest_xray.jpeg`

These files are not included in this repository. Update the paths in the notebook if the files are stored elsewhere.

## Data Sources

- [UCI Heart Disease dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- [UCI Heart Failure Clinical Records dataset](https://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records)
- [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)
- [Breast Cancer Wisconsin dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

## Disclaimer

These notebooks are educational examples only. Their outputs are not medical advice, diagnoses, or validated clinical tools.
