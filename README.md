# hand-writtendigit-recognition-all-
KMNIST (Kuzushiji-MNIST) contains 70,000 28x28 grayscale images spanning 10 classes (one from each column of hiragana), and is perfectly balanced like the original MNIST dataset (6k/1k train/test for each class). Different loss function and optimizer combinations were used . Got a state of the art accuracy of 96.13% with categorical crossentropy as loss function and Adam as optimiser.

I implemented a deep learning model (with 4 CNN and 1 dense and 1 output layer)on MNIST and I augmented the dataset (eg; with zoom in, rotation, horizontal and vertical shifting) and got a testing accuracy of 99.51%.

Kuzushiji-49, as the name suggests, has 49 classes (28x28 grayscale, 270,912 images), is a much larger, but imbalanced dataset containing 48 Hiragana characters and one Hiragana iteration mark.I implemented a simple cnn model on the dataset with Adam optimizer and categorical crossentropy as loss function.
