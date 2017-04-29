# Conditional-Image-Generation-Project

##INTRODUCTION

This is the repository of IFT6266H17 project.

More detail about the project description to see(https://ift6266h17.wordpress.com/project-description/)

##Prerequisites

- tensorflow 0.1.1

- python 3.5

##Usage

If you clone the the whole repository, just ignore Train step.

  Train:
  
    $ python3 train-cdcgan.py -dataset ./data/train2014 --epoch <epoch>
  
  Test:
  
    $ python3 test-cdcgan.py -dataset ./data/val2014/* --outDir testImages
