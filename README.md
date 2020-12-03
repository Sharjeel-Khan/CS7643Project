# CS7643: Deep Learning Project (The CheXperts)

## Project Outline
1. [Getting Started](#started)
    1. [Prerequisites](#prerequisites)
    2. [Files](#files)
2. [Running Code](#code)
3. [Results](#results)
    1. [AUROC Reproducability Scores](#reproducability)
    2. [Siamese AUROC Scores](#siamese)


## Getting Started <a name="started"></a>

### Prerequisites <a name="prerequisites"></a>

These are the software needed:
* Python (3.5+)
* Pip
* Matplotlib
* Jupyter
* Scikit-Learn
* Pytorch

### Files <a name="files"></a>
* Ignore.ipynb: Code for reproducability of U-ignore
* ChexpertMultiClass.ipynb: Code for reproducability of U-Multiclass
* SemiSupervised.ipynb: Code for reproducability of U-SemiSupervised
* Siamese_Enlarged_Cardio.ipynb: Code for siamese network on Enlarged Cardio
* Siamese_Lung_Lesion.ipynb: Code for siamese network on Lung Lesion
* Chexpert_Siamese_Multiclass.ipynb: Code for Siamese network on Pneumonia and Atelectasis


## Running Code <a name="code"></a>
Each jupyter notebook has both the training code and evaluation code. If you train a new model, you need to get the name of the saved model and edit it in the notebook to test the model. There are pre-trained models that we have trained and put in the respective folders. 

## Results <a name="results`"></a>

### AUROC Reproducability Scores <a name="reproducability"></a>
![U-Ignore](/graphs/auc_u_ignore.png)

![U-Binary](/graphs/auc_u_binary.png)

![U-Learning](/graphs/auc_u_learning.png)

![U-MultiClass](/graphs/auc_u_multiclass.png)

### Siamese AUROC Scores <a name="siamese"></a>

![Enlarged Cardio.](/graphs/auc_Enlarged_siamese.png)

![Atelectasis](/graphs/auc_atelectasis_siamese.png)

![Pneumonia](/graphs/auc_pneumonia_siamese.png)

![Lung Lesion](/graphs/auc_Lung_lesion_siamese.png)

## Authors

* **Sharjeel Khan**
* **Vidisha Goyal**
* **Sheryl Ratnam**
* **Raghav Apoorv**
