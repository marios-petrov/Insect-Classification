# Insect Species Classification with ResNet50

## Introduction
This project leverages ResNet50, a deep learning model, to classify insect species. The model's application to entomology showcases how transfer learning and neural networks can intersect to enhance biological classification tasks.

## Dataset
An imbalanced collection of insect images from Kaggle serves as the dataset, mirroring the common ecological data scenario with variable species prevalence.

## Model Overview
The core of this project is ResNet50. Its performance, with and without pre-trained weights, provides insights into transfer learning's effect on specialized tasks like insect classification.

## Model Architechture
![Untitled Diagram drawio](https://github.com/marios-petrov/Insect-Classification/assets/118226559/ba99d705-136c-458e-b484-3413c8ca928c)

## Results
The pretrained ResNet50 demonstrates high accuracy and stability. In contrast, the non-pretrained model shows performance variability.

## Discussion
Challenges identified in classification, such as distinguishing between ladybugs and mosquitoes, point to future research avenues. Refining the focus to classify species within specific genuses and enhancing the dataset with quality images are prospective steps.

## Future Directions
Moving forward involves dataset expansion with high-quality images and fine-tuning the classification to narrower taxonomic categories for better ecological significance.

## How to Use
1. Clone the repo.
2. Install dependencies.
3. Use the Jupyter notebooks provided for training and model evaluation.

## Citation
Please cite the following if this project aids your research:
1. Don Chathurika Amarathunga, John Grundy, Hazel Parry, and Alan Dorin. 2021. Methods of insect image capture and classification: A systematic literature review. Smart Agricultural Technology 
2. Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. 2015. Deep residual learning for image recognition. arXiv.org. Retrieved December 9, 2023 from https://arxiv.org/abs/1512.03385.
3. Monika Mathur, Diksha Vasudev, Sonalika Sahoo, Divanshi Jain, and Nidhi Goel. 2020. Crosspooled fishnet: Transfer learning based fish species classification model. Multimedia Tools and Applications 79, 41–42: 31625–31643. 
4. Oskar L. Hansen, Jens‐Christian Svenning, Kent Olsen, et al. 2019. Species‐level image classification with convolutional neural network enables insect identification from habitus images. Ecology and Evolution 10,
5. Hammad Ali. 2020. Insects recognition. Kaggle. Retrieved December 10, 2023 from https://www.kaggle.com/datasets/hammaadali/insects-recognition

## Contact
For queries or contributions, please open an issue or submit a pull request.

---
Created by Marios Petrov for the Machine Learning Final Project at New College of Florida, Sarasota, FL.
