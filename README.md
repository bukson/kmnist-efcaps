<h1 align="center"> Improved Efficient Capsule Network for Kuzushiji-MNIST Benchmark Dataset Classification </h1>

This repository is cloned version of [Efficient-CapsNet](https://github.com/EscVM/Efficient-CapsNet) which contains code that we developed to train model
for categorizing Japaneese characters [Kuzushiji-MNIST dataset](https://github.com/rois-codh/kmnist). 



#  Installation

1. Clone this repository
   ```bash
   git clone https://github.com/bukson/kmnist-efcaps
   ```
2. Install the required packages
   ```bash
   pip3 install -r requirements.txt
   ```

# Purpose

Out purpose is to used modified network architecture and components from Efficient Capsule Networks
to create model for Kuzushiji-MNIST dataset. We show that it is possible to make deep capsule architecture,
train it on consumer grade pc setup in few gpu hours on dataset with high number of classes and achieve
competitive results comparing to more complicated and expensive architecture (4th place for KMNIST and 6th place for Kuzushiji-49) [Kuzushiji-MNIST benchmark](https://paperswithcode.com/sota/image-classification-on-kuzushiji-mnist). 

We also like to popularize Efficient Capsule Networks as it is extremely well written piece
of software, that can be easily modified by other scientist and repurpose or use to check others result.
This is in our knowledge a rare case among other Capsule Network modifications.



# K49 and KMNIST Notebooks

In notebooks directory you can find notebooks that we used to train our models.

[kmnist_train_test.ipynb](notebooks%2Fkmnist%2Fkmnist_train_test.ipynb) contains code for training and testing model on KMNIST dataset.

[k49_train_test.ipynb](notebooks%2Fkmnist%2Fk49_train_test.ipynb) contains code for training and testing model on K49 dataset.

