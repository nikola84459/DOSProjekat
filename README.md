Description:

The goal of this project is to detect the presence of a brain tumor based on images from magnetic resonance imaging (MRI).

The process begins with image preprocessing to ensure successful classification:

Image Loading and Display: First, images are loaded from a folder and displayed.

SNR (Signal-to-Noise Ratio) Calculation: The noise level in the images is calculated, and the SNR index is graphically displayed to visualize the noise level.

Image Interpolation: The image is resized using the BICUBIC interpolation algorithm.

Noise Removal: The noise is removed from images where the SNR index is lower than 1.

Image Segmentation: Segmentation is applied to enhance the region of the image where the tumor is located, improving the classification accuracy.

Neural Network Creation: A neural network is created to be used in the classification process, followed by training.

The accuracy percentage after training is 88.57%.
