# Introduction to Machine Learning (Classification Assignment)
Author: Evert Duipmans
Date: 29-8-2019

Goal of the project is to write a digit recognizer using Scikit-Image and Scikit-Learn. The additional packages that you need are Python 3.6 (or higher), NumPy, Pandas, Jupyter and Matplotlib.

## Folders
This folder contains several sub folders, each with a specific goal. Please maintain this structure!

- **notebooks**: this folder will contain all of your notebooks.
    - Make sure that your notebook names are numbered.
    - Make sure that the author name and student number is present in the notebook.
    - Notebooks are considered a combination of documentation and code. Document your work properly with MarkDown.
- **dataset-images**: this folder contains all the images of the dataset.
    - Each image is 128x32 pixels. Each 32x32 image represents one digit.
- **dataset-numpy**: this is the folder where you store your feature vectors (using joblib or pickle).
    - There should be at least one dataset for pixel-based features (counts, etc.).
    - There should be at least one dataset with vision-based features (height, width, perimeter, number of holes, etc.).
- **classifiers**: this folder contains your exported classifiers (including your final model).
    - Export each classifier using joblib or pickle.
    - Import your best model in the final notebook and make sure that we can score your classifier properly.
- **homework**: this folder should contain your homework assignments of the first 4 weeks.
