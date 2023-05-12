# Deepfake-Generation-and-Detection
Deepfake detection is necessary in medical image analysis to prevent the creation and spread of manipulated medical images that can have serious consequences for patient diagnosis and treatment. Hence, we will attempt to build a machine learning model and train it to carry out detection between original images and deepfakes created and analyze them.

The project’s design is split into 3 parts - creation of deepfakes, training of the models on the original dataset and then choosing the best model and training it on the deepfakes dataset. The model used for deepfake creation was DCGAN, and there were four models used for training on the original dataset (custom-made CNN, ResNet18, ResNet50 and MobileNetV2). 

To illustrate the difference between deepfake images and original ones we select the model which achieved the highest accuracy on the original dataset and run that model on the newly created deepfake images. Our proposed methodology should achieve a comparatively lower accuracy on the deepfake images, hence allowing us to detect them.
