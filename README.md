# Tweets Sentiment Classification using CNN

## Dataset
The dataset used in this experiment : https://www.kaggle.com/c/tweet-sentiment-extraction/overview
![image](https://user-images.githubusercontent.com/54148951/180595076-bb41837b-f893-4a3e-984b-30b60c50f092.png)


![image](https://user-images.githubusercontent.com/54148951/180595176-34f9651f-e548-4f56-94e2-fdaf44ea674b.png)


## Library
* matplotlib
* tensorflow
* pandas
* numpy
* sklearn

## Text Preprocessing
* remove emoji
* remove url
* lowercase
* remove punctuation

## Train, Valid and Test Data Distribution
|          |   Train    |   Valid    |   Test   |   
|----------|------------|------------|----------|
|  Neutral |   9.633    |    1.071   |   1.376  |
| Positive |   7.537    |     838    |   1.075  |
| Negative |   6.906    |     767    |    983   |

## CNN Model
![image](https://user-images.githubusercontent.com/54148951/180595663-0a4912e2-f68b-49fe-9b9c-9416a13a16ea.png)

## Hyperparameter
* Epochs = 20
* Batch = 16
* Max Features = 20.000
* Embedding Dim = 64
* Sequence Length = 40
* Verbose = 1


## Result
- Still overfitting to train data
### Loss
![image](https://user-images.githubusercontent.com/54148951/180595720-2ab448cf-36a5-4646-9d68-8464c5f55170.png)

### Categorical Accuracy
![image](https://user-images.githubusercontent.com/54148951/180595737-4d7f83c3-3a72-4350-83c1-6c168c4383da.png)

### Classification Report
![image](https://user-images.githubusercontent.com/54148951/180595758-b0390bdb-72ef-499a-a032-d6d86e0f2e7f.png)

## References:
https://www.youtube.com/watch?v=MsL79ZIqWpg&t=792s
