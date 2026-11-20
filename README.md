# Pattern Recognition — Course Projects

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

My solutions to the assignments of the **Pattern Recognition** course at Amirkabir University of Technology (Tehran Polytechnic), M.Sc. in Artificial Intelligence and Robotics (Fall 2024) · Instructor: **Prof. Mohammad Rahmati**.

Each folder contains the code (Jupyter notebooks / Python scripts) and the full written report with results and analysis.

## Assignments

| Assignment | Topics | Main tools | Files |
|---|---|---|---|
| [Linear Algebra & SVD Recommender](HW1-Linear-Algebra-and-SVD-Recommender) | Eigen-decomposition and diagonalization; SVD-based recommender with mean and KNN imputation | NumPy, SciPy | [code](HW1-Linear-Algebra-and-SVD-Recommender/code) · [report](HW1-Linear-Algebra-and-SVD-Recommender/report.pdf) |
| [Bayes Decision Theory & ROC](HW2-Bayes-Decision-Theory-and-ROC) | Bayes decision rule, error bounds (Bhattacharyya), parameter estimation, ROC curves on Wine Quality | scikit-learn | [code](HW2-Bayes-Decision-Theory-and-ROC/code) · [report](HW2-Bayes-Decision-Theory-and-ROC/report.pdf) |
| [K-Nearest Neighbors](HW3-K-Nearest-Neighbors) | k-NN and weighted k-NN, cross-validation and leave-one-out, heart-disease classification | scikit-learn | [code](HW3-K-Nearest-Neighbors/code) · [report](HW3-K-Nearest-Neighbors/report.pdf) |
| [PCA, LDA & SVD Denoising](HW4-PCA-LDA-and-SVD-Denoising) | PCA and LDA from scratch, K-Means, patch-based SVD image denoising, feature selection on breast-cancer data | NumPy, scikit-learn | [code](HW4-PCA-LDA-and-SVD-Denoising/code) · [report](HW4-PCA-LDA-and-SVD-Denoising/report.pdf) |
| [SVM & Clustering](HW5-SVM-and-Clustering) | Linear discriminants, kernel SVM on facial landmarks (dlib), topic discovery on BBC News with K-Means and hierarchical clustering | scikit-learn, dlib, gensim | [code](HW5-SVM-and-Clustering/code) · [report](HW5-SVM-and-Clustering/report.pdf) |

## How to run

```bash
git clone https://github.com/Aidin-Khalili/Pattern-Recognition-Course-Projects.git
cd Pattern-Recognition-Course-Projects
pip install numpy pandas scipy scikit-learn matplotlib seaborn opencv-python dlib gensim nltk
jupyter notebook
```

Most notebooks were run on Google Colab or locally; paths to data files may need to be changed to your own.

## Notes

- Reports are written in English (HW5 in Persian).
- Large datasets, model weights and course-provided input files are not included. Some figures in the notebooks were compressed or removed to keep the repository small; the full set is in each `report.pdf`.

## License

Released under the [MIT License](LICENSE): you are free to use, modify and share this code with attribution.

## Author

**Aidin Khalili** — [GitHub](https://github.com/Aidin-Khalili)
