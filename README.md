# Classification-of-Cifar10-images-using-convolutional-networks
## **Overview**<br>
This data set contains 32 x 32 color images in 10 different classes, including cars, trucks, horses, etc., which are available in the keras framework and we use the same.<br>
<br>
You can read more information about this dataset from the site of this dataset:<br>
https://www.cs.toronto.edu/~kriz/cifar.html<br>
## **Conclusion**<br>
In this code, I used 2 convolutional networks architecture; the model gained the below result as its first architecture:<br>

**Final test set loss: 0.9303**<br>
**Final test set accuracy: 0.6716**<br>


I changed the network architecture(added a dropout layer) and hyperparameters(changed the number of epochs, and batch size) to maximize the accuracy of the test data, this is the result of my second model:<br>

**Final test set loss: 0.848305**<br>
**Final test set accuracy: 0.707400**
