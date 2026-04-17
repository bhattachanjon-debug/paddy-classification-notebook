I developed a Convolutional Neural Network (CNN) using PyTorch for paddy leaf disease classification. 
The dataset was preprocessed using torchvision transforms, including resizing images to 128×128 
and converting them into tensors.

The model architecture includes stacked convolutional layers with ReLU activations 
and max-pooling layers for feature extraction, followed by fully connected layers for classification. 
The model was trained using the Adam optimizer with cross-entropy loss.

For inference, the trained model was evaluated on the test dataset using a DataLoader, 
and predictions were obtained by selecting the class with the highest score. 
These predictions were mapped to their corresponding class labels to generate the final submission.

This serves as a baseline deep learning model, with opportunities for improvement through techniques such as 
data augmentation and transfer learning.
