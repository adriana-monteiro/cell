# Cancer Blood Cell Classification: A Deep Learning Project

This is a project made for the Deep Learning course of the Master's in Data Science and Advanced Analytics of NOVA IMS. The objective was to use deep learning techniques to solve a supervised machine learning problem. The chosen problem was an image classification task of blood cell cancer detection (details in [here](https://www.kaggle.com/datasets/mohammadamireshraghi/blood-cell-cancer-all-4class)). All code was done in a Google Colab environment.

## Key Project Components:
The project is divided in different jupyter notebooks:
1. Data Exploration ([explore.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/explore.ipynb))
   * Analysis of images from each class, duplicates, ...;
2. Data Preprocessing ([preprocessing.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/preprocessing.ipynb))
   * Data Augmentation;
   * Image Transformations;
   * Base Model to evaluate the preprocessing.
3. Model Handcrafting ([model handcrafted.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/model%20handcrafted.ipynb))
   * Implementation of different CNN configurations (Custom made CNNs, ResNet, VGG);
   * Prediction results with different scores (accuracy, recall and precision)
4. Model Hyper Search ([model hyper search.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/model%20hyper%20search.ipynb))
   * Hyperameter optimisation (hyperband and random search).
5. Transfer Learning  ([model handcrafted.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/transfer.ipynb))
    * Transfer Learning using ResNet50V2
6. Optional technique: TensorBoard ([optional_1.ipynb](https://github.com/adriana-monteiro/cell-cancer-classification/blob/main/notebooks/optional_1.ipynb))

### Group Members:
- Adriana Monteiro
- Inês Nascimento
- Janaina Santos
- Stanislav Slesarev
- Samuel Santos
