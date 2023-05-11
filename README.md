## Project Description
<br>
I trained a Convolutional Neural Network (CNN) in this study to detect whether a chest x-ray indicates the presence or absence of TB, using the Shenzhen CXR dataset. I handled all aspects of the CNN architecture design, data preparation, data augmentation, and model training. I first separated the training and testing data from the original dataset and used ImageDataGenerator to preprocess and enrich the training dataset. The CNN architecture includes four Conv2D layers and a MaxPool2D layer. The output of the final MaxPool2D layer is flattened, then passed through three Dense layers, each with a Dropout layer, before being activated via the sigmoid function. The model was created using the Adam optimizer and binary_crossentropy loss. Following training on the dataset, I tested the model on the testing dataset, achieving an accuracy of approximately 82.85%.
<br>
<br>

## Model Architecture
<br>

![circuit diagram](Model_Architecture.png
)
