# Image-Augmentation
This Python script uses the Augmentor library to perform data augmentation on images in the specified input_directory and saves the augmented images to the output_directory. It applies various transformations to increase dataset diversity, helping machine learning models generalize better.

Key Steps:
Input and Output:

input_directory: Folder containing the original images.
output_directory: Folder where augmented images will be saved.
Transformations:

Random rotation, flip, zoom, brightness/contrast adjustment, skew, and shear are applied to the images.
Generate Augmented Images:

pipeline.sample(500): Creates 500 new augmented images using the specified transformations.
Result:

Augmented images are saved in the output_directory.
Output:
500 augmented images are generated and saved, introducing variations like rotation, flipping, and brightness adjustments, enhancing the dataset for better ML training.
