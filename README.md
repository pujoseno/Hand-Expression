# Hand-Expression
Using CNN to Train Gesture Image for Hand Expression.

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
 
### There are 2 directories:
* gesture : Contains images the eleven classes of gesture
* hand_emo: Contains images hand emoticon with eleven classes

### files:
* BuatCSV.py : Used to create or convert CSV file
* BuatGest.py : Used to create hand gesture for dataset
* Hand_Exp.py : Used to Prediction model and to show hand expression
* TrainHandExp.py : Used to training our model
* Gesture : Hand gesture dataset 
* hand_exp.h5 : Model from process training

### How to Run

1) Run BuatGest.py (`python BuatGest.py`) to create hand gesture. In this step we using 1200 image in each gesture.
2) Repeat this for all the features you want.
3) Run BuatCSV.py (`Python BuatCSV.py`) for converting the images to a CSV file, and you have the csv file in your directory.
4) Train the model using TrainHandExp.py (`python TrainHandExp.py`)
5) Finally, for testing the model run Hand_Exp.py (`python HandExp.py`)

### Reference

[Akshay Bahadur](https://github.com/akshaybahadur21/Emojinator)
[Explanation](https://github.com/akshaybahadur21/Emojinator)
 
 
<img src="https://github.com/pujoseno/Hand-Expression/blob/master/hand_exp.gif">
