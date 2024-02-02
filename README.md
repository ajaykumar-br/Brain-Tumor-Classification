# Brain Tumor Classification on BraTS 2019 Dataset

## Overview
This project leverages advanced neural network architectures for classifying brain tumors using the BraTS 2019 dataset. It employs a customized U-Net and an AlexNet model, both optimized with transfer learning. Implemented in Google Colab, this project aims to push the boundaries of medical image analysis.

## Features
- **Data Visualization**: Implementation of the nilearn library for comprehensive visualization of MRI data.
- **Custom U-Net Model**: Achieved an impressive accuracy of 99.6% while segmenting the tumor from the image.
- **AlexNet Model with Transfer Learning**: Attained a commendable accuracy of 98.3% while classifying one in multiple classes.
- **Performance Metrics**: In-depth performance analysis including accuracy, loss, dice loss.

## Dataset
The project uses the BraTS 2019 dataset, consisting of a variety of MRI scans of brain tumors, pre-processed for model training.

## Requirements
- Google Colab
- Python 3.x
- Nilearn
- TensorFlow 2.x
- Keras

## Installation
The project is hosted on Google Colab, requiring no additional installation.

## Results
The models demonstrate exceptional performance in classifying brain tumors:

### Customized U-Net Model
- Input Size: 128x128x2
- Output Size: 128x128x4
- Optimizer: Adam
- Learning Rate: 0.001
- Batch Size: 1
- Epochs: 165
- Loss Function: Categorical Cross Entropy, Dice Loss
- Accuracy: 99.6%
- Loss Value: 0.0116
- Dice Loss Value: 0.7427

### AlexNet Model
- Input Size: 128x128x2
- Output Size: 128x128x4
- Optimizer: Adam
- Learning Rate: 0.001
- Batch Size: 1
- Epochs: 60
- Loss Function: Categorical Cross Entropy, Dice Loss
- Accuracy: 98.3%
- Loss Value: 0.1073
- Dice Loss Value: 0.0010

Detailed visual results and analyses are included within the Colab notebooks.

## Contributing
Contributions are welcome. Please fork the project and submit a pull request for any improvements.

## License
[MIT License](https://choosealicense.com/licenses/mit/)
