# MNISTHandwrittenDigits

Python notebook for Kaggle competition on recognising handwritten digits by MNIST.
[Link](https://www.kaggle.com/c/digit-recognizer/overview) to the competition.

The architecture of my CNN model : In -> \[Conv2D\(relu) -> Conv2D\(relu) -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense\(relu) -> Dropout -> Out

Training for 100 epochs \(approximately 3s per epoch), I got a training accuracy of 98.52% and a validation accuracy of 99.35%
