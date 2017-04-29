# Conditional-Image-Generation-Project
This is the repository of project for IFT6266H17
The test code for Conditional Generative Adversarial Nets using tensorflow.

##INTRODUCTION
Project repository for IFT6266H17
For more detail about the project description(https://ift6266h17.wordpress.com/project-description/)

##Prerequisites

- tensorflow 0.1.1

- python 3.5

##Usage
If you clone the the whole repsitory, just ignore Train step.
  Train:
  
    $ python3 train.py -dataset ./data/train2014 --epoch <epoch>
  
  Test:
  
    $ python3 test.py -dataset ./data/val2014/* --outDir testImages
