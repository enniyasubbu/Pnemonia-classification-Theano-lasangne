# Pnemonia_Classification_using_Theano_Lasagne
Pnemonia_Classification_using_Theano_Lasagne using Convolutional Neural Network

## How to use the Repo
    1.Open Image_classification.py
       set these paameter before running the program
        DATASET_PATH=""
        TEST_DIR=""
        BATCH_SIZE="Based on your gpu"
        EPOCHS=''
        set all the above parametershttps://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/kernels
        The code performs confusion matrix and graph to visualize the train loss, validation loss and test loss in realtime
        Execute in Terminal= python2 image_classification.py
        The best models are snapshoted and saved in a directory  
## Results
    Dense units=128 Accuracy=82.5 Epochs=28
     Dense units=256 Accuracy=84.1 Epochs=18
     Dense units=512 with Roll Augmentation Accuracy=86.2 Epochs=36

## Datasets
   The dataset has been used from Kaggle competition
  
   https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/kernels




   
    
