Dental Image segmentation

# Data split
dataset consists of a total of 989 images, which were randomly divided into training, validation, and test sets with a split of 70% for training, 20% for validation, and 10% for testing. This division was achieved using a Python script named data_split.py, which also saves dataset lists in the data.json file. Additionally, it stores class names and class weights for segmentation.


`evaluation.py`
computes evaluation metrics over the training, validation, and test datasets and saves the Dice score for each image in the file `evaluation_results.csv`

`gui.py`
renders the gui for to uplload image and visualize segmentation and save file.