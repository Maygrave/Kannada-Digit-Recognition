# Kannada Digit Recognition

### General Overview

The Kannada digit recognition competition is devloped with the MNIST project as its inspiration. The MNIST data is a well known data set consisting of hand drawn digits, frequently used and reviewed in convolutional nerual networks (CNNs). These networks are taught to accurately distiguish the digits from one another. In a twist on this original goal, [this kaggle competion][1] presents data on digits from the Kannada language, and invites competitors to build the most accurate model for identifying these new digits. In this project, I seek to accomplish exactly this goal, by creating my own CNN in order to distinguish the Kannada digits.

<img align="left" style="border:10px solid white" width = 300 src="Images/Dravidian_subgroups.png" alt = "A map showing the locations in which ceratin Dravidian language family members are spoken."> Kannada is a member of the [Davidian language family][2], a group of related languages which are spoken mainly in southern India. Kannada is the third most spoke language in the family, with approximately 44 million native speakers, and roughly 56 million total speakers. The language is written using the Kannada script, throughly without roman/arabic influence, with its roots in the 5th century Kadamba script.

With a uniquely different style of writing, this challenge both allows new data scientists to get their hands dirty building CNN models and hardened competitors to experiment with old MNIST models on new data. To this end, three data sets are presented on the [kaggle competiion page][1]: a training set, `train.csv`, a validation set, `Dig-MNIST.csv`, and a testing set, `test.csv`. All three sets contain image data, with the first two also containing information labels for the images.

### Data Treatment and Augmentation
The image data for this challenge first needed transformed before it could be visualized or modeled. The original data was organized such that each row of a data frame referenced a single image, with the first column of the data showing the label of the image, and the remaining 784 columns each representing one pixel in the 28x28 pixel image. The pixel value is shown as an integer between 0 and 255, inclusive.

### The Model


#### Data Treatment and Augmentation


#### Model Architecture


#### Training Step 1


#### Training Step 2


#### Training Step 3


### Requirements
The dependancies for this project can be found in the the `requirements.txt` file.

<!---References--->
[1]: https://www.kaggle.com/c/Kannada-MNIST/overview "Kaggle Competition"
[2]: https://en.wikipedia.org/wiki/Dravidian_languages "Wikipedia Dravidian Language Image Source"
