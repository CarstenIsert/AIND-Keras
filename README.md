### Instructions

1. Originially, this repo was forked from https://github.com/udacity/aind2-dl.git

	Either take the code directly from there to do your own work or download the code from my repo. Clone the repository and navigate to the downloaded folder:
	```	
		git clone https://github.com/CarstenIsert/AIND-Keras.git
		cd AIND-Keras
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
	
	For __Mac/OSX__ or __Linux__:
	```
		conda env create -f aind-dl-mac-linux.yml
		source activate aind-dl
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

3. Start the notebook
	``` jupyter notebook Student_Admissions.ipynb ```
	or
	````jupyter notebook IMDB_In_Keras.ipynb```
	
4. The notebooks contain observations and results analyzing the models and the code. 
