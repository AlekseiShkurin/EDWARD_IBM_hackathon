###THE CNN INTERFACE
*CNN Interface is aimed to afford user to run convolutional neural network for image 
classificstion and customize it according to the data used. It provides basic*

####File list
--------------------------------------------------------------------------------------------------------------------------
Classifier:
* **logistic_sgd.py**		Multi-class logistic regression
* **mlp.py**			Multilayer perceptron
* **convolutional_mlp.py**	Convolutional neural network

Interface:		
* **tryconsole.py**		Starts calculations on the console
* **testdesign.py** 	Graphical interface
* **executework.py**		Execution code

Run **executework** to launch interface.

####Requirements & Guide
--------------------------------------------------------------------------------------------------------------------------
Packages: theano, numpy, scipy, pillow, six<br />
Python version: at least 3.4.X<br />
Data: zipped directory containing numerical named folders with images(class per folder)<br />
Format: zip. file<br />
IMG format: .jpg<br />


This directory contains the code for implementation



####Parameters
-------------------------------------------------------------------------------------------------------------------------
Basic settings:
* Amount of layers: № of convolutional layers.
* Batch size: № of training examples in a forward-back pass.
* Amount of epochs: № of forward-backward pass of all the training examples.
* Size of pooling: 		

Advanced:
* GPU: For higher performance GPU might be used.
* Size of filter: Size of a matrix looking for a particular feature (depends of image size).
* Learning rate: Control of weights and biases.

>Note:<br />
We restric parameters to optimal numbers to minimize human error.<br />
>

*Sincerely,*<br />
*Stayin' Alive Team.*
