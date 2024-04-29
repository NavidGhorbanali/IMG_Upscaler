This Repository Contains A Pytorch Implementation of Ledig, C., Theis, L., et al. (2017), also known as the SRGAN model. Included are a few sample images of it action after 100 epochs of training in the "Examples" folder.

HOW TO USE
------------
Put your chosen Training Data into "Train_HR" and the Validation Data into "Validate_HR"
Create two folders named "Statistics" and "Epochs".
The Trainer takes 3 optional Arguments: The upscale factor which can be either 2,4 or 8, the Size of the Crop, and the number of training epochs.
The Test Image takes 4 optional Arguments: the upscale factor, the test mode (either gpu or cpu), the model name, and the image name.
