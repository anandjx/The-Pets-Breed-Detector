# The-Pets-Breed-Detector

This project focuses on the training of a Convolutional Neural Network (CNN) and its ability to categorise the breed of a pet using the Oxford-IIIT Pet Dataset. The dataset includes pictures of cats and dogs of 37 various breeds, so the database is rather useful in training of models that are intended to be used in the recognition of pets.
The first one is to train from the raw data a baseline CNN this model allows having an initial conception about the process of image classification. The first model works as reference performance shows the obstacle and constrain of applying simple CNN architecture on complicated dataset.

To improve the model performance to the best extent possible, we then use Transfer Learning with EfficientNet B2, which is one of the most efficient and high performing architectures for the tasks of computer vision. Given a network we start with, we adopt a pre-trained EfficientNet B2 model, and further train the model for the purpose of pet breed categorization. This greatly enhances the models capability since the pre-trained network is not only able to identify deeper characteristics about the images.

This way for the given task it will be shown how much the transition from a simple CNN to transfer learning and from there to more complex EfficientNet B2 model may improve both accuracy and the models ability to generalize.

Further We will use Gradio demo to deploy this model for a web browser.

![6947bdc6-9661-4f3d-aea9-82269f1c2993](https://github.com/user-attachments/assets/77796ae9-a201-408b-8816-606c0fa3a214)
