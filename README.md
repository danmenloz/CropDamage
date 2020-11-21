# CropDamage
Image segmentation of damaged crops using SegNet arquitecture.

* Model is trained in 'Segnet.ipynb' which loads the architecture from 'segnet_model.py', saves the best parameters in 'segnet_best.pth' and it also generates the 'datasets.csv' file to keep track of the datasets used for training, validation and test.

* Model performance is evauluated in 'Segnet Evaluation.ipynb' which loads the model from 'segnet_best.pth' the dtasets info from the 'datasets.csv'  file to properly compute the scores.

* Finally, predictons are stored in the 'predict_segnet' directory.
