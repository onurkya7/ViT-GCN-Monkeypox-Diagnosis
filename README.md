# ViT-GCN-Monkeypox-Diagnosis

Accurate diagnosis of monkeypox is challenging due to the limitations of current diagnostic techniques, which often fail to account for the complex visual and structural characteristics of skin lesions. This project introduces a novel hybrid deep learning approach that integrates the strengths of **Vision Transformers (ViT)**, **ResNet50**, and **AlexNet** with **Graph Convolutional Networks (GCN)** to enhance diagnostic accuracy. 

- **Binary Classification**: Achieved 100% accuracy.
- **Multi-Class Classification**: Reached a 97% accuracy rate.

## Models
  - `GCN-Alexnet-binaryclass.ipynb` - Implementation of the GCN-AlexNet model for binary classification.
  - `GCN-Alexnet-multiclass.ipynb` - Implementation of the GCN-AlexNet model for multi-class classification.
  - `GCN-Resnet50-binaryclass.ipynb` - Implementation of the GCN-ResNet50 model for binary classification.
  - `GCN-Resnet50-multiclass.ipynb` - Implementation of the GCN-ResNet50 model for multi-class classification.
  - `GCN-ViT-binaryclass.ipynb` - Implementation of the GCN-ViT model for binary classification.
  - `GCN-ViT-multiclass.ipynb` - Implementation of the GCN-ViT model for multi-class classification.

Each model notebook contains code for training and evaluating a specific hybrid model architecture on either binary or multi-class datasets.

## Setup Environment

1. Clone this repository to your computer:

    ```bash
    git clone https://github.com/onurkya7/ViT-GCN-Monkeypox-Diagnosis.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ViT-GCN-Monkeypox-Diagnosis
    ```

## Contributing

If you want to contribute to this project, please follow these steps:

- **Fork:** Fork this repository to your GitHub account.
- **Create a Branch:** Create a new branch to add a new feature or fix a bug.
- **Commit:** Add clear commit messages explaining your changes.
- **Push:** Push your changes to the repository you forked.
- **Pull Request:** Create a pull request on GitHub.

## License

Our project is licensed under the [GNU General Public License v3.0](LICENSE).

