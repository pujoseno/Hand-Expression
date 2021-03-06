# Hand-Expression
Using CNN to Train Gesture Image for Hand Expression. In this case we will implementation CNN model in image recognition. In this case we using hand gesture images. What the benefit in this case? we can learn about how CNN work in Image recognition and how to prediction hand gesture Using CNN. 

### Requirements
You can install requirements in this repo.

##### pip install requirements.txt

### Structure
* Hand-Expression
  * hand_emo
    * 1
    * ---
    * 11
  * gesture
    * 1
    * ---
    * 11
  * BuatCSV.py
  * BuatGest.py
  * TrainHandExp.py
  * Hand_Exp.py
  * hand_exp.h5
  * train_gest.csv
 
### There are 2 directories:
* gesture : Contains images the eleven classes of gesture
* hand_emo: Contains images hand emoticon with eleven classes

### files:
* BuatCSV.py : Used to create or convert images to CSV file
* BuatGest.py : Used to create hand gesture for dataset
* Hand_Exp.py : Used to Prediction model and to show hand expression
* TrainHandExp.py : Used to training our model
* train_gest.csv : Contains matrix pixel from images
* Gesture : Hand gesture dataset 
* hand_exp.h5 : Model from process training
* model.png : Model CNN

### Model
<img src="https://github.com/pujoseno/Hand-Expression/blob/master/model.PNG">

### How to Run

1) Run BuatGest.py (`python BuatGest.py`) to create hand gesture. In this step we using 1200 image in each gesture.
2) Repeat this for all the features you want.
3) Run BuatCSV.py (`Python BuatCSV.py`) for converting the images to a CSV file, and you have the csv file in your directory.
4) Train the model using TrainHandExp.py (`python TrainHandExp.py`)
5) Finally, for testing the model run Hand_Exp.py (`python HandExp.py`)

### Reference

#### [Akshay Bahadur](https://github.com/akshaybahadur21/Emojinator)
#### [Explanation](http://thinkstudioo.blogspot.com/2018/07/hand-expression-menggunakan-convolution.html)
 
<img src="https://github.com/pujoseno/Hand-Expression/blob/master/hand_exp.gif">
