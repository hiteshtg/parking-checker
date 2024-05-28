Data set = https://drive.google.com/drive/folders/1tX0aeKMKZe3vI3_1BWdFADe5QzJgDO2c?usp=drive_link

This program is on Computer Vision.
Trying to solve Car parking/Parking Lot problem. This model show us about parking lot if it is empty or not.

This used Bagging Classification and  Support Vector Machine.SVC(i.e. Support Vector Classification) to classify whether the lot is empty or not.

Bagging Classification is used to create multiple SCV models and to combine them to increase accuracy of model.
SVC is the core model that is used to classify whether parking lot is empty or not.

Data Preprocessing:
1. Data is first catagorised into 2 empty and not_empty.
2. Then using a loop all the images are read and converted into matrix.
3. All the flatten matrix are then appended into 2 list, which is then converted into array.
4. Then data and lables are ready to be used to train our machine learning model.
5. Data is splitted into train and valid/test data which is actually used to train model.

Accuracy of the model is then calculatted using accuracy_score.

This model is then used in a video to calculate the number of available spot in a Car Parking Facility.

/home/hitesh/ksnip_20240528-123804.png
