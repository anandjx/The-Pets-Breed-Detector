# The-Pets-Breed-Detector

This project focuses on the training of a Convolutional Neural Network (CNN) and its ability to categorise the breed of a pet using the Oxford-IIIT Pet Dataset. The dataset includes pictures of cats and dogs of 37 various breeds.
The first one is to train from the raw data a baseline CNN this model allows having an initial conception about the process of image classification. The first model works as reference performance shows the obstacle and constrain of applying simple CNN architecture on complicated dataset.

To improve the model performance to the best extent possible, we then use Transfer Learning with EfficientNet B2 model, which is one of the most efficient and high performing architectures for the tasks of computer vision. Given a network we adopt a pre-trained EfficientNet B2 model, and further train the model for the purpose of pet breed categorization. This greatly enhances the models capability since the pre-trained network is able to identify deeper characteristics about the images.

This way for the given task it will be shown how much the transition from a simple CNN to transfer learning and from there to more complex EfficientNet B2 model may improve both accuracy and the models ability to generalize.

Further we use Gradio to deploy this model for a web browser.

![Screenshot 2024-08-17 170641 2](https://github.com/user-attachments/assets/8e5297eb-a9b1-40b0-a026-11d4548b98b9)
![6947bdc6-9661-4f3d-aea9-82269f1c2993](https://github.com/user-attachments/assets/22e45bf1-b875-443e-813d-01aebd76ff1b)


