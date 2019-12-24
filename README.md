# DM19-Lab2-Homework

### Part 2, Part 3 are at competition.ipynb

### Data Preprocessing
* replace some special text by regularize words(EX: @ERIC ===> USER ,EX: 25 times ===> NUM times)

### CNN-LSTM model
* The best of the result of my CNN-LSTM model is 0.469. This model i didn't do any preprocessing for the data.
* I try to imporve it, so i make some data preprocessing like remove the stop words, special charts, @.... but the result become worse.(almost 0.45X)
* I find out if i use pre-trained words embedding(glove), i don't need to do the work i mentioned above. I think the reason is due to the special type in twitter.
* I also try to use LSTM-CNN model instead, but the result is worse then CNN_LSTM model.(almost 0.44 ~ 0.45)

### Bert
* I do the data preprocessing I mentioned above (EX: @ERIC ===> USER , 25 times ===> NUM times ...etc). Regularize special type of twitter.
* The best result of my model is 0.527
