# Machine Learning for Chirp Detection
A program to generate sample polynomial phase chirps and identify noisy chirps using Machine Learning. 
The model used was a Support Vector Machine (SVM) which was trained on 1500 generated chirps. 

## Images 
![Example Chirp](imgs/example_chirp.png) </br>
<strong> An Example Chirp generated </strong> </br>

![Example Chirp](imgs/noisy_chirp.png) </br>
<strong>A Noisy Chirp generated </strong> </br>

![Example Chirp](imgs/match_filtering.png) </br>
<strong> Using Matched Filtering to identify which chirp is the noisy one based off </strong> </br>
![Example Chirp](imgs/confusion.png) </br>
<strong> Testing a SVM model using a confusion matrix </strong> 

## Dependencies
* Jupyter Notebook
* Python 3.7 or above
* SciKit-Learn
* Pandas
* Numpy 
* Matplotlib 
* Pickle
* Cmath </br>
<strong> All libraries are included with the most recent version of Anaconda </strong> 

## Authors
David Luong, Carleton Univeristy  <br />
Dr. Sreeraman Rajan, Carleton University  <br />
Omar Imran, Carleton University  

This project was funded by the I-CUREUS grant provided by the Carleton University Discovery Center.
