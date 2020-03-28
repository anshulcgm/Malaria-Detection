# Malaria-Detection

This project was inspired by a kaggle dataset containing images of cells infected with malaria and cells that were uninfected. The challenge was to create a Machine Learning model that could distinguish whether a given picture of a cell was infected with malaria or not. The model was a Convolutional Neural Network created in Keras. The model had 3 convolution layers along with several Leaky ReLU and  MaxPooling layers. Finally, the output after all these layers was fed to a Multi Layer Perceptron which produced a final decision of whether the cell was infected or not. Additionally, the model incorporated dropout layers to reduce overfitting and to improve generalization. The results were as follows:

Training Accuracy: 99.1%

Training Precision: 98.9%

Training Recall: 99.5%

Validation accuracy: 94.5%

Validation precision: 93.7%

Validation recall: 95.2%

Test accuracy: 94.2%

Test precision: 94.1%

Test recall: 94.6%
