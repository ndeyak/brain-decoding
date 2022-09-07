# Brain decoding project

The work involved decoding neural activity from fMRI scans of the motor cortex. Three regions were scanned, namely the S1, M1 and SMA. These regions were scanned while a participant performed hand movements for the rock-paper-scissors games. The aim of the project is to classify which brain activity pattern represented by voxels is rock, paper, or scissors.

We used 2 linear (Logistic Regression and SVM) and 2 non-linear (KNN and Decision Trees) classifiers and observed that the linear classifiers performed much better than the non-linear classifiers. This is because fMRI data is linear. 

The code consists of two notebooks:
1) hyperparam_selection.ipynb, which was used to select the best hyperparameters for training the classifiers; and
2) project decoding brain activity.ipynb, which is mucher neater, uses the best hyperparameters for the 4 classifiers choosen.
