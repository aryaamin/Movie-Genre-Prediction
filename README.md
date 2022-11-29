# Movie-Genre-Prediction
<pre>
1) DATASET

  Dataset comprises of Movie Posters(Multi_Label_dataset/Images) and their Genres(Multi_Label_dataset/train.csv).

  Link: https://www.kaggle.com/datasets/raman77768/movie-classifier
</pre>
<pre>
2) HOW TO USE

  Download dataset archive from above link and extract it in the working directory(Group32_Project).

  Also keep the group32_aiml.py in the same folder(Group32_Project).
</pre>
<pre>
3) DIRECTORY STRUCTURE

  Group32_Project/group32.py
  Group32_Project/group32.ipynb
  Group32_Project/Multi_Label_dataset/Images
  Group32_Project/Multi_Label_dataset/train.csv
  Group32_Project/References.txt
  Group32_Project/README.txt
</pre>
<pre>
4) MODEL

  Three Models used:
    ->Baseline Algorithm
    ->KNN
    ->Custom Architecture(SimpleCNN)
</pre>
<pre>
5) ARCHITECTURE

  Input: [400*300*3]: the raw pixel values of the poster image
  Output: [25]: Labels(0 or 1) of 25 genres.(1 means correct genre)
</pre>
<pre>
6) LIBRARIES
  numpy
  torch
  torchsummary
  torchviz
  matplotlib
  sklearn
  tqdm
  keras
</pre>
<pre>
6) REFERENCES
  https://colab.research.google.com/github/FreeOfConfines/ExampleNNWithKerasAndTensorflow/blob/master/K_Nearest_Neighbor_Classification_with_Tensorflow_on_Fashion_MNIST_Dataset.ipynb#scrollTo=E95EztQIZyl1
  https://www.kaggle.com/datasets/raman77768/movie-classifier                       
  https://github.com/leosouliotis/cnn_poster
</pre>
