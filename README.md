# lung-cancer-classification
RESNET ENCODER FOR LUNG CANCER CLASSIFICATION
1. An implementation of an encoder decoder architecture for the segmentation of lung dataset.
2. The dataset used is the LIDC/IDRI DATASET
3. Images are first converted to 3 dimensional format to help the easy flow of the RESNET encoder 
which takes a 3 channel image as an input.
4. A dynamic decoder is then built to upsample the downsampled image from the encoder.
