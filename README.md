# Project-DL-
This project is about Hip fracture X ray with deep learning 
ReadMe:

Or Benson - 308577345
Omri Plotink - 308516905

 ** Disclaimer: For this assignment I used the following articles:

	https://github.com/jacobgil/pytorch-grad-cam
	https://github.com/facebookresearch/moco



 The file is divided into 3 parts: The notebook should not be run unless one wants to inspect other parts of the code. The notebook inspects:

Part One – Project DL

	Import and downloads:

	Mount to Drive: Press the provided link, copy the validation code, paste into the box and press enter. 
	Change to a relevant path: Change the path in “path” to a desired directory to be able to open/save the data from the Drive folder.

	Creating Datasets
	In “Project DL” we define the transformations to be applied to the images. This way we augment the dataset, allowing for better generalization and helping prevent overfitting

	Running different nets:
	Make sure you got all the data been created and, in the directory, you crated 
	Run the nets but the different fit cells
	Make sure you put a different number of epochs in each net. 

	Summary of results:
	Get different convolutions for each net
	Get different grad come of each net













Part two- Self Supervise Model:

	Import and downloads:

	Mount to Drive: Press the provided link, copy the validation code, paste into the box and press enter. 
	Change to a relevant path: Change the path in “path” to a desired directory to be able to open/save the data from the Drive folder.

	Avoiding from changing the data path 

	Creating Datasets
	In “Self Supervise” we define the transformations to be applied to the images. This way we augment the dataset, allowing for better generalization and helping prevent 

	Summary of results:
	Get different convolutions for each net

Part Three - GAN Model:

	Import and downloads:

	Mount to Drive: Press the provided link, copy the validation code, paste into the box and press enter. 
	Change to a relevant path: Change the path in “path” to a desired directory to be able to open/save the data from the Drive folder.

	Creating Datasets:

	For the first run we're going to create the base network class, this way we can define steps that are general for training and data handling that’s independent (to a certain degree) of the specific network architecture.
	Run the GAN model with 500 epochs and LR of 2*e^(-4)

	Summary of results:
	Get different convolutions matrix for each net











![image](https://user-images.githubusercontent.com/95141744/207653895-b7affcf1-ccc9-4ab8-b428-16af9410a037.png)
