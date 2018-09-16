# Multilayer-Neural-Network-for-Handwritten-Digit-Classification
Multilayer Neural Network for Handwritten Digit Classification

Summary
•	Network takes 1 image as an input at a time
o	Basically, 784 1-D input as each image is 28x28 matrix
•	Provided with 60,000 Training images and 10,000 Testing Images, each with a ‘desired output’ in the form of a Label file.
•	Network produces 10 outputs (1 output for each digit expected)
•	For each input, took the index of the maximum of the 10 induced local fields right before the 10 output fields and compared it with the   Label for that specific image to determine correct classification or misclassification
	    Ex: If 3rd induced local field is the max, then the input image will be classified as the digit 3
