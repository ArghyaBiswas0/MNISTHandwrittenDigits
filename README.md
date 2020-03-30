# MNISTHandwrittenDigits

Python notebook for Kaggle competition on recognising handwritten digits by MNIST.
[Link](https://www.kaggle.com/c/digit-recognizer/overview) to the competition.

Download the data from [here](https://www.kaggle.com/c/digit-recognizer/data) and put the CSV files in the same folder as the notebook.

The architecture of my CNN model : In -> \[Conv2D\(relu) -> Conv2D\(relu) -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense\(relu) -> Dropout -> Out

Training for 100 epochs \(approximately 3s per epoch), I got a training accuracy of 98.52% and a validation accuracy of 99.35%
