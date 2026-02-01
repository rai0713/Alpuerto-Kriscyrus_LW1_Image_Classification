# Alpuerto-Kriscyrus_LW1_Image_Classification

[Google Colab Link](https://colab.research.google.com/drive/1popFc4hAX3rs1Uc5YfqrVM0QdiYS9OB_?usp=sharing)
Questions:
1. What is the Fashion MNIST dataset?
Answer: Fashion MNIST dataset is the one who gives the premade data clothing and accessories images and fixed images where it cannot be changes, this MNIST data set is been handwritten digits (0-9) and there is 10 categories of it: T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot.

2. Why do we normalize image pixel values before training?
Answer: We normalize it to be a fast and reliable for neural network., because if there is a lot of pixels, meaning the neural networks need to do a lot of math which will make the training heavy and slow, since they also calculate multiply weights and sum them, so if pixel is big then it will be heavy, now since it will be divided by 255 which is from black to white, it will be range only 0 - 1 still maintaining the color but lowering those pixels.

3. List the layers used in the neural network and their functions.
Answer: In the code we use, there is three layer, first when we flatten layer, we take the 28x28 image and we will transform them to 784 by multiplying them, it will transform into 1D. Second one is Dense Layer which have 128 neurons workers with ReLU activation so we can make the flattened image analyze by this neurons, ReLU on other is ignores negatives numbers and it keeps only the positive so it can learn like shapes and edges so they can decide what patterns is important, and the Third one is Dense Layer only (No ReLU) that it outputs the  10 scores for each clothing, the highest score represents the predicted class.

4. What does an epoch mean in model training?
Answer: Epoch is how many times you will train images so it can learn and learn till the loss is less and the success or accuracy is high

5. Compare the predicted label and actual label for the first test image.
Answer: The predicted label in the first image is 9 which is the Ankle Boot then the actual label is 9 Ankle Boot. Therefor, we can say that the model predicted it correctly

6. What could be done to improve the model’s accuracy?
Answer: There is so many ways to improve this, such as:
Adding more layers because this will deeper the network and can learn more complex patterns,
Increasing Neurons or Use Other Activation so it will have a good meural network and will be more accurate as they work for the patterns and ignore more negativity which is not important,
Training longer or adding more epochs will also help the accuracy more higher. Therefore, I conclude that there is more other way to do this since my knowledge is limited.
