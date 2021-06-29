# Sports-Celebrity-Image-Classification

---

A dataset consisting 5 sports celebritries are used for image classification. Classification models such as SVM, Logistic Regression and Random Forest are used. 

Following steps are performed for classification:


*   Data Collection:
For this project, I am downloading a small dataset from: https://github.com/codebasics/py/tree/master/DataScience/CelebrityFaceRecognition/images_dataset


*  Cleaning Dataset:
   OpenCV is used to detect face and eyes. All those images where two eyes are not properly visible are discarded.
 
 
*  Feature Engineering:
   Wavelet transform is used to extract important features of the face.
 
 
*  Training Model for Classification:
   SVM, Logistic Regression and Random Forest are used for classification. GridSearchCV is used for hyperparameter tuning.
   
   
Reference: https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ
    
   
