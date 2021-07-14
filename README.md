# TruncpinTSVM
Robust Transductive Support Vector Machie using Truncated Pinball loss
pin¯-TSVM: A Robust Transductive Support Vector Machine and its Application to the Detection of COVID-19 Infected Patients


We are very thankful to the authors of “Large-scale robust transductive support vector machine” to make their code public. 


Contents: 

In this folder, pin_transductive_svms_real.m is the main MATLAB file here. This function further uses two functions: train_linear_pin_svm_robust_dual.m and train_linear_pin_svm_sg_robust.m for implementing the dual formulation and the SGD based implementation of the proposed technique.
In this folder, we have also attached various data sets used in this implementation. These are:
Sonar (208×60): To classify two types of sonar signals: one bounced off a roughly cylindrical rock and those sonar signals which bounced off a metal cylinder. For feature details and the complete data set, readers are referred to the URL: https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)

Cleveland Heart (303×75): To classify patients based on presence or absence of heart disease. For feature details and the complete data set, readers are referred to the URL: https://archive.ics.uci.edu/ml/datasets/heart+disease

Haberman (306×3): Classification based on the survival status of patients (who died within 5 years or patients who survived 5 years or longer) who had undergone surgery for breast cancer. For feature details and the complete data set, readers are referred to the URL:
https://archive.ics.uci.edu/ml/datasets/Haberman's+Survival

WDBC (569×32): Features describe the characteristics of the nuclei of the cell present in the images. It classifies if the case is benign or malignant. For feature details and the complete data set, readers are referred to the URL:
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

Australian (690×14): The task is to classify the applications approved for credit card. For feature details and the complete data set, readers are referred to the URL: http://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)

Pima Indians (768×8): Based on the women living in Arizona and the task is to classify them as diabetic or non-diabetic. For feature details and the complete data set, readers are referred to the URL: https://www.kaggle.com/uciml/pima-indians-diabetes-database

CMC (1473×9): The task is to predict the contraceptive method choice of a woman based on her socio-economic and demographic characteristics. For feature details and the complete data set, readers are referred to the URL:  https://archive.ics.uci.edu/ml/datasets/Contraceptive+Method+Choice

Spambase (4601× 57): To classify an email as spam or non-spam. For feature details and the complete data set, readers are referred to the URL: https://archive.ics.uci.edu/ml/datasets/Spambase
Banana (5300×3): An artificial data set where instances belongs to several clusters with a banana shape. There are two attributes At1 and At2 corresponding to the x and y axis, respectively. The class label (-1 and 1) represents one of the two banana shapes in the dataset. For feature details and the complete data set, readers are referred to the URL: https://www.openml.org/d/1460

Page Blocks (5473×10): The problem consists of classifying all the blocks of the page layout of a document that has been detected by a segmentation process. For feature details and the complete data set, readers are referred to the URL https://archive.ics.uci.edu/ml/datasets/Page+Blocks+Classification

Musk Version 2(6598×168): The goal is to learn to predict whether new molecules will be musks or non-musks. For feature details and the complete data set, readers are referred to the URL https://archive.ics.uci.edu/ml/datasets/Musk+(Version+2)
Cats vs Dogs (25000×2): To classify the new image as cat image or dog image. For feature details and the complete data set, readers are referred to the URL: https://www.kaggle.com/c/dogs-vs-cats/data
CIFAR-10 (60000): CIFAR-10 data set has 60,000 color images of size 32×32 pixels. These
images belong to ten classes. To use this data set, we extract features from the image data set. For feature details and the complete data set, readers are referred to the URL : https://www.cs.toronto.edu/~kriz/cifar.html

MNIST (70000): MNIST database comprise of images of handwritten digits. The task is to
identify the new digit based on the image. For feature details and the complete data set, readers are referred to the URL: http://yann.lecun.com/exdb/mnist/

Cover Type (581012×54): The task is to predict the forest cover type based on the cartographic
Variables. It includes a total of seven classes marked as integer 1 to 7 in the data set. For feature details and the complete data set, readers are referred to the URL:  https://archive.ics.uci.edu/ml/datasets/covertype

For information related to covid data set, please see COVID readme file.

We have also attached the folder for “mlcv_Quadprog_1.0” to use the function mlcv_quadprog().
