# NLP - Feature Extraction

This project contains the implementation of the following preprocessing and features of a signal:

1. Importing speech file and sampling
2. Preprocessing
	1. Frame blocking
	2. Windowing
	3. Preemphasis
3. Extract features
	1. Time-domain features
		1. Mean
		2. Energy
		3. ZCR (Zero Crossing Rate)
		4. Auto-correlation
			1. Normal implementaion
			2. Implementing by Multiplying the signal to a power of an odd number
			3. Implementing with Center Clipping
			4. Implementing with 3-level Center Clipping 
		5. AMDF (Average Magnitude Difference Function)
	2. Frequency-domain features
		1. FFT (Fast Fourier Transform)
		2. LPC (Linear predictive coding)
		3. Cepstral Analysis
		4. Spectrum Estimation
			1. Spectrum Estimation based on FFT
			2. Spectrum Estimation based on LPC
		5. Pitch Estimation
			1. Pitch Estimation based on Auto Correlation

Also, the used libraries in this project are as follows:

* `librosa`: a python package for music and audio analysis
* `scipy`: a free and open-source Python library used for scientific computing and technical computing
* `matplotlib`: a comprehensive library for creating static, animated, and interactive visualizations in Python
* `numpy`: a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays
