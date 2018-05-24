
To run the project

Compatible operating systems: a.	Windows 7, 8, 10 b.	Mac OS c.	Linux Ubuntu 15.04 and above
Install Python Development kit
Install the following python libraries of the corresponding versions a.	opencv-python==3.2.0.6 b.	h5py==2.6.0 c. matplotlib==2.0.0 d.	numpy==1.12.0 e.	scipy==0.18.1 f.	tqdm==4.11.2 g.	keras==2.0.2 h.	scikit-learn==0.18.1 i. pillow==4.0.0 j.	tensorflow==1.0.0
Install Jupyter notebook
Before running the program remember to create a dataset, if the CNN has to be trained for new individuals remember to train the CNN for the particular individuals. To start: a.	Go to ‘humanImages’ and make a folder for each of the individuals in the ‘train’, ‘test’ and ‘valid’ folders with the same name. b.	Save the images in these named folders. Make sure the images are different for the same individual in the ‘train’, ‘test’ and ‘valid’ folders. c.	‘train’ folder should have at least 75% of the images. d.	Once this is done, the dataset has been created. e.	Add additional images to be predicted in ‘whoisthis’ folder
Run the Jupyter notebook
In the Jupyter notebook, run the ‘finalCode.ipynb’
Set the value of the variable ‘subjects’ to the number of individuals the CNN has to recognize from.
Run each of the code segment sequentially as the flow is important and see the results. ***The user must know how to use a Jupyter notebook. This notebook was used due to its ability to run the codes in parts. With the help of this notebook we can also run the code from a remote server like the AWS and the Google cloud instance. Please refer to https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/ for reference.
