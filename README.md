# nip_project

# files

Data was obtained from the following Kaggle dataset :  https://www.kaggle.com/karangadiya/fifa19

training_set and test_set.csv files provide the file path to training pictures and test pictures.

nip_project.ipynb is the notebook that downloads the images and train/test split. Pictures are in the "faces" folder

nip_project_model.ipynb is the notebook that preprocesses the data and trains the model with it.

# Rationale

While reading this article: https://www.vocativ.com/culture/sport/shape-soccer-players-face-predicts-performance/index.html, I was wondering if I could replicate such results using a convolutional neural network by taking in the players' faces as input, and predicting how aggressive each player is.

# Improvements

Utilize transfer learning with a good pre-trained model. Limitations: Current dataset has 15000 faces; most transfer learning cases have lesser data. Can still try in the future if I have a better computer.
