# Project_Skin_Cancer

Welcome to our skin cancer detection project, where we leverage cutting-edge deep learning techniques to enhance the accuracy and efficiency of skin disease classification. In this repository, we have implemented the Convolutional Block Attention Module (CBAM) layer to amplify both Channel Attention and Spatial Attention mechanisms within our neural network architecture.

![Skin Cancer Detection](https://raw.githubusercontent.com/OthmanMoussaoui/Skin_Cancer_detection/main/Skin_Cancers.png)

## About the Dataset
The dataset used in this project is sourced from Kaggle's "Skin Cancer MNIST: HAM10000" dataset, available [here](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000). It comprises a diverse collection of skin lesion images, providing a robust foundation for training and testing our model.

## Project Highlights

### CBAM Integration
Our model's key innovation lies in the incorporation of the Convolutional Block Attention Module (CBAM). This strategic addition enhances the network's ability to capture intricate features associated with skin diseases. By recalibrating channel-wise and spatial-wise information, CBAM allows the model to focus on relevant regions while effectively suppressing irrelevant ones. This results in a more discriminative representation of skin lesions.

### Hyperparameter Tuning
To optimize the training process, we adopted a reduced learning rate strategy and employed the Stochastic Gradient Descent (SGD) optimizer. This meticulous tuning of hyperparameters has played a pivotal role in achieving remarkable results. The model showcases an impressive accuracy of 93%, reflecting the success of our approach in enhancing diagnostic performance.

### Creative Approach
Our commitment to creativity extends beyond the architecture itself. By combining CBAM integration with thoughtful parameter adjustments, we demonstrate the potential for improved diagnostic performance in skin disease classification. This project serves as a testament to the power of innovative techniques in pushing the boundaries of medical image analysis.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Download the dataset from Kaggle and place it in the designated data directory.
3. Install the required dependencies using the provided `requirements.txt` file.
4. Run the training script to train the model on the skin cancer dataset.
5. Explore the trained model's performance and make predictions using the provided notebooks.

Feel free to experiment, contribute, and let your creativity shine in improving the diagnostic capabilities of our skin disease classification model. Together, we can make a significant impact in the field of medical image analysis. Happy coding!
