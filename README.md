# Data Science & AI

I created this repository while learning **Data Science** and **AI**. After each lesson, I committed the code I wrote and the knowledge I gained. So each commit captures a step in my learning journey. You'll find everything here: from NumPy and Pandas fundamentals all the way to deep learning models. 

## Project Structure

```
data-science-and-ai/
├── data-science/
│   ├── numpy-lessons/          # NumPy from basics to linear algebra (14 lessons)
│   ├── pandas-lessons/         # Pandas Series, DataFrame, indexing, operations (20 lessons)
│   ├── Regression/             # Simple, multiple, and polynomial regression
│   ├── classification/         # Logistic regression, K-NN, decision trees, confusion matrix
│   ├── unsupervised-learning/  # K-Means, DBSCAN, hierarchical clustering
│   ├── visualization/          # Matplotlib, Seaborn, scatter plots, heatmaps, subplots
│   └── ML-project-steps/       # End-to-end ML workflow: data prep → pipeline → modeling
│
└── deep-learning/
    ├── perceptron.ipynb
    ├── neural-networks.ipynb
    ├── activation-function.ipynb
    ├── loss-function-and-optimization.ipynb
    ├── loss-function-and-optimization-part-2.ipynb
    ├── classifying-pictures-with-CNN.ipynb
    ├── creating-simple-rnn.ipynb
    ├── nlp-part-2.ipynb
    └── configuring-pretrained-models.ipynb
```

## Topics Covered

### Data Science
| Module | Topics |
|--------|--------|
| **NumPy** | Arrays, data types, indexing/slicing, boolean indexing, universal functions, sorting, linear algebra, file I/O |
| **Pandas** | Series & DataFrame, indexing (loc/iloc/at/iat), reindexing, filtering, arithmetic, sorting, ranking, statistics, correlation |
| **Regression** | Simple linear, multiple linear, polynomial regression |
| **Classification** | Logistic regression, K-Nearest Neighbors, decision trees, confusion matrix analysis |
| **Unsupervised Learning** | Clustering fundamentals, DBSCAN, hierarchical clustering |
| **Visualization** | Matplotlib intro, scatter plots, distribution (KDE/CDE), heatmaps, subplots, Seaborn |
| **ML Project Workflow** | Real-world data handling, data preparation, pipelines, model building |

### Deep Learning
| Topic | Description |
|-------|-------------|
| **Perceptron** | Building the fundamental unit of neural networks |
| **Neural Networks** | Multi-layer architecture and forward/backward propagation |
| **Activation Functions** | ReLU, sigmoid, tanh, softmax and their roles |
| **Loss & Optimization** | Loss functions, gradient descent, optimizers (SGD, Adam, etc.) |
| **CNN** | Convolutional Neural Networks for image classification |
| **RNN** | Recurrent Neural Networks for sequential data |
| **NLP** | Natural Language Processing techniques |
| **Pretrained Models** | Configuring and fine-tuning transformer models |

## Setup

### Data Science environment

```bash
cd data-science
pip install pipenv
pipenv install
pipenv shell
```

### Deep Learning environment

```bash
cd deep-learning
pip install pipenv
pipenv install
pipenv shell
```

**Python version:** 3.11+

**Key libraries:**
- **Data Science:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Deep Learning:** PyTorch, Torchvision, Transformers, Datasets, Accelerate

## Usage

1. Clone the repository
2. Set up the environment for the module you want to explore
3. Launch Jupyter:

```bash
jupyter notebook
```

4. Open notebooks in order — each lesson builds on the previous one
5. Run cells interactively and experiment with the code

## Datasets

Some notebooks use local CSV files included in the repository (e.g., `merc.csv`, `uzb.csv`, `data.csv`). For deep learning notebooks, datasets are downloaded programmatically via `torchvision.datasets` or Hugging Face `datasets` library.
