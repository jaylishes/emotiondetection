# Emotion Detection


# Preperation

  - Download and extract fer2013 to root directory
  - Download and extract shape_predictor_68_face_landmarks.dat to root directory
  - Solve package dependencies from Jupyter Notebooks

# Data preperation

 - Load convert_extract-ipynb in Jupyter Notebook
 - Execute Cells beginning from top ("convert pixels from csv to image, save labels = emotions and landmarks" may take a while because it's transforming the pixels from csv to images)
 
# Training

 - Load train.ipynb in Jupyter Notebook
 - Execute Cells beginning from top, exclude last one
 - acc: Accuracy with training data

# Validate

 - Load train.ipynb in Jupyter Notebook
 - Execute Cells Constants and the last cell
 - Printed value is accuracy with validation data