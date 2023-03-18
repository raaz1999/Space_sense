# Space_sense
train a ML model on the EuroSAT land cover classification dataset

Constraints of the current solution:

* The model has a slow training process, especially without transfer learning.
* Overfitting is observed, where the accuracy of the train set is higher than that of the validation set.
* The model struggles to differentiate similar images, such as pastures and a green lake.

Potential improvements to the solution:

* Implement Optuna, a library that can test different parameters such as the learning rate, number of layers, etc., to find the optimal solution.
* Explore other pre-trained models for transfer learning, such as ResNet, that are trained on similar topics and may improve the model's performance.
* Increase the available GPU resources to speed up the model's training and testing process.
* Apply data augmentation techniques such as horizontal flip, grayscale, etc. to increase the number of samples and gather more information about the labels with lower examples.
