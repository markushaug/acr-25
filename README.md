# Performance of Machine Learning Classifiers for Anomaly Detection in Cyber Security Applications
Code for published research paper for the 2025 International Conference on Advances in Computing Research (ACR’25) which took place in Nice, France, July 7-9, 2025.

- Markus Haug*, Gissel Velarde
- IU International University of Applied Science, Erfurt, 99084, Germany
- markus.haug@iu-study.org, gissel.velarde@iu.org

## Instructions

1. Clone the repository
2. Create a new virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

3. Install the dependencies

```bash
pip install -r requirements.txt
```

4. Open the Jupyter notebooks

## Cite this work

If you use this code or reference the results in your research, please cite the following publication:

```bibtex
@InProceedings{10.1007/978-3-031-87647-9_25,
    author="Haug, Markus
    and Velarde, Gissel",
    editor="Daimi, Kevin
    and Al Sadoon, Abeer",
    title="Performance of Machine Learning Classifiers for Anomaly Detection in Cyber Security Applications",
    booktitle="Proceedings of the Third International Conference on Advances in Computing Research (ACR'25)",
    year="2025",
    publisher="Springer Nature Switzerland",
    address="Cham",
    pages="285--294",
    abstract="This work empirically evaluates machine learning models on two imbalanced public datasets (KDDCUP99 and Credit Card Fraud 2013). The method includes data preparation, model training, and evaluation, using an 80/20 (train/test) split. Models tested include eXtreme Gradient Boosting (XGB), Multi Layer Perceptron (MLP), Generative Adversarial Network (GAN), Variational Autoencoder (VAE), and Multiple-Objective Generative Adversarial Active Learning (MO-GAAL), with XGB and MLP further combined with Random-Over-Sampling (ROS) and Self-Paced-Ensemble (SPE). Evaluation involves 5-fold cross-validation and imputation techniques (mean, median, and IterativeImputer) with 10, 20, 30, and 50 {\%} missing data. Findings show XGB and MLP outperform generative models. IterativeImputer results are comparable to mean and median, but not recommended for large datasets due to increased complexity and execution time. The code used is publicly available on GitHub (github.com/markushaug/acr-25).",
    isbn="978-3-031-87647-9"
}
```
