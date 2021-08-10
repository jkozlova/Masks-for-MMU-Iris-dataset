# Masks for MMU Iris dataset

The repository contains **ground-truth segmentation masks** for [MMU Iris Database](http://pesonna.mmu.edu.my/ccteo/). This database was originally provided by Multimedia University. You can also find the original dataset in alternative sources on the Internet (see [the dataset on Kaggle](https://www.kaggle.com/naureenmohammad/mmu-iris-dataset), etc).

We performed manual segmentation of the entire data set containing 450 images of the eyes (45 persons, 10 images for each person). 

The ground-truth segmentation masks are supposed to be used for the assessment of the segmentation quality of iris images.

# Publications

This repository was used when preparing the following article:
* Title: "Identifying a person by iris images using a neural network approach for the segmentation and feature extraction"
* Authors: Yu.Kh. Ganeeva, E.V. Myasnikov 
* Journal: Computer Optics

# Structure of Repository

The data structure in the repository is as follows:

`Dataset` 
```         
├──── mask/
    ├──── 1/
       ├──── left/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
       ├──── right/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
    ├──── 2/
       ├──── left/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
       ├──── right/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
    ...
    ├──── 45/
       ├──── left/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
       ├──── right/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
```


# Acknowledgments

We thank our colleagues from MultiMedia University and personally Chuan-Chin Teo for providing the original [MMU Iris Database](http://pesonna.mmu.edu.my/ccteo/).


