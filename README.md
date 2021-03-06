# PROMISE12_OptUNet
An optimised U-Net for prostate segmentation evaluated on PROMISE12 test set. 

Architecture used in paper "[Optimisation of 2D U-Net Model Components for Automatic Prostate Segmentation on MRI](https://www.mdpi.com/2076-3417/10/7/2601)"
based on Keras.

The code is in jupyter notebook and it consists of step-by-step guide/tutorial for performing semantic segmentation on MRI. 

No pre-trained models or test results provided to reduce the possibilities of training on the test set.  

# Getting Started
1. Download the repository.
2. Ensure that the dependencies are installed. 
    - Tensorflow >= 1.12.0
    - Keras >= 2.2.4
    - Sklearn >= 0.19.1
    - Cv2 >= 3.4.4
    - Numpy >= 1.15.4
    - Matplotlib >= 2.2.2
    - Skimage >= 0.13.1
    - SimpleITK  
3. Download PROMISE12 training set, unzipped it and place it in TrainData folder.
4. Download PROMISE12 test set, unzipped it and place it in TestData folder.
5. Run the jupyter notebook.

# Acknowledgements
Keras: Keras.io
