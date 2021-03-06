# face-emotion-detection

### Data-set

First thing first, let's see which data was used and what was inside it. 
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories 

label   |    category
------|----------------
0|Angry
1|Disgust
2|Fear
3|Happy
4|Sad
5|Surprise
6|Neutral

Here is what training data look like: 
![title](https://github.com/nirajdevpandey/face-emotion-detection/blob/master/data-set/training_data.PNG)


Here is what test data look like: 
![title](https://github.com/nirajdevpandey/face-emotion-detection/blob/master/data-set/test_data.PNG)

train.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order. test.csv contains only the "pixels" column and your task is to predict the emotion column.

The training set consists of `28,709` examples. The public test set used for the leaderboard consists of `3,589` examples.

This dataset was prepared by `Pierre-Luc Carrier` and `Aaron Courville`, as part of an ongoing research project. 

Trained model can be found in the repository itself. Special thanks to `B-IT-BOTS` robotics team for such a wonderful resources and the pretrained models. https://mas-group.inf.h-brs.de/?page_id=622

Please stay tuned, i'll upadte the readme very soon. Thanks 
