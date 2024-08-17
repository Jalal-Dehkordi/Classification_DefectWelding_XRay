# Welding Defect Classification using Deep Learning on X-Ray Images
## Project Overview
This project focuses on the classification of welding defects using deep learning techniques applied to industrial radiography (X-Ray) images. The goal is to leverage advanced deep learning models to accurately classify different types of welding defects captured in radiographic images. The research methodology is comprehensive, ensuring precise and reliable results.

## Dataset
The primary dataset used in this research is the RIAWELC dataset, which contains a diverse collection of high-quality radiographic images of welding defects. The dataset is selected due to its quality and the variety of defects it encompasses. The images are categorized into four main classes:

* Lack of Penetration (LP)
* Crack (CR)
* Porosity (PO)
* No Defect (ND)

   
The dataset consists of 24,407 images, each resized to 224x224 pixels and stored in JPEG format. The dataset is divided into a larger set (DataSet A) and a smaller set (DataSet B) to facilitate the training and evaluation of models under different conditions.

## Models Used
Several pre-trained deep learning models were employed in this research for the classification task. These models are known for their effectiveness in various domains, including medical and industrial radiography. The models used include:

* Xception
* NASNet Mobile
* DenseNet201
* InceptionV3
* ViT-B/16
* SqueezeNet V1.1
* VGG16
* VGG19
* ResNet50V2
* MobileNet V2
* EfficientNet B1
* ResNet50
* ResNeXt50_32x4d
* ShuffleNet V2
* AlexNet
  
These models were chosen for their proven success in previous research and their ability to accurately extract features from radiographic images, making them ideal for defect classification.

## Research Methodology
1. Data Preparation
   
The dataset was processed by extracting the welding areas from the images, which were then divided into smaller tiles (80x80 pixels) for easier analysis. Contrast enhancement was applied using the Contrast-Limited Adaptive Histogram Equalization (CLAHE) technique to improve defect visibility.

3. Model Training

The models were initially trained on DataSet A, which contains a larger number of images, and then evaluated on DataSet B, a smaller subset of the original dataset. This two-stage training process allowed for the evaluation of model performance under different data availability scenarios.

4. Transfer Learning and Fine-Tuning

Transfer learning techniques were employed, using pre-trained models as a starting point to reduce the computational resources required. Fine-tuning was then applied to adapt the models to the specific task of welding defect classification.

5. Evaluation and Comparison

Each model’s performance was thoroughly evaluated to determine the most effective approach for classifying welding defects. The use of multiple models allowed for a detailed comparison and identification of the best-performing model for this task.

## Results and Practical Applications
The results of this research demonstrate the potential of deep learning models in improving the accuracy and efficiency of welding defect classification in industrial settings. The findings can be directly applied in the welding industry to enhance quality control processes, reduce inspection costs, and ensure the structural integrity of welded components.

## Tools and Technologies
This project was implemented using the following tools and frameworks:

* TensorFlow
* Keras
* PyTorch
* TensorFlow Hub
  
These tools provided the necessary environment for developing, training, and evaluating the deep learning models used in this research.

## Conclusion
This research highlights the importance of using advanced deep learning techniques for the classification of welding defects in industrial radiography. The two-stage training process, combined with the use of a high-quality dataset and a variety of pre-trained models, ensures that the results are both accurate and practical for real-world applications.

