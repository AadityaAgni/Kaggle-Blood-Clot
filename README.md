# Kaggle-Blood-Clot
My Solution to the Mayo Clinic Blood Clot Classification Competition

The competition revolved around differentiating between the two major acute ischemic stroke (AIS) etiology subtypes: cardiac and large artery atherosclerosis.

This solution uses OpenSlide to tile a large part of the image in order to resize it to get around the problem of the massive image size.
  


The difficulty behind this classification task was:
  1. The large file size of each image(30k+*30k+) images
  2. The imbalance of data(around 2x the amount of CE examples versus LAA)




** Credit to this notebook for the some of the parts I used: https://www.kaggle.com/code/jonathanma02/cnn-blood-clot-origin-classifier **
