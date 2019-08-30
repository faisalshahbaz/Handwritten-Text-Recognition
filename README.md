# OCR
This project refers to the handwritten recognition with CNN and RNN, decode with CTC.

<<<<<<< HEAD
![alt text](https://github.com/tuandoan998/OCR_IAM-dataset/blob/master/Resouce/demo.png)
=======
![alt text](https://github.com/tuandoan998/OCR_IAM-dataset/blob/master/Resource/demo.png)
>>>>>>> 63517bc25b5c29384eeb19e792a2346122094e55

## Dataset
[IAM dataset](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database/download-the-iam-handwriting-database)  
Train on WORD unit of dataset.

## Model
![alt text](https://github.com/tuandoan998/OCR_IAM-dataset/blob/master/Resource/model.png)

## Result
Test on IAM dataset:

|  Unit | Number of samples | CER(%) | WER(%) | 
| :-    |     :---:         |  ---:  |  ---:  |
| WORD  | 19289             | 10.75  | 27.46  | 
| LINE  | 2192              | 21.73  | 46.00  | 

## Main

### Preprocessing

### Train

### Postprocessing

### Evaluation


## Usage

### Train
```
$ python3 Train.py
```

### Predict
```
$ python3 Prediction.py
```
![alt text](https://github.com/tuandoan998/OCR_IAM-dataset/blob/master/Resource/test_img/Screenshot.png)

### Evaluation
```
$ python3 Evaluation.py
$ python3 Evaluation_Line.py
```

## References
https://towardsdatascience.com/build-a-handwritten-text-recognition-system-using-tensorflow-2326a3487cd5
http://norvig.com/spell-correct.html
