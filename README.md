# MMU-Iris-Mask


The repository was created within the framework of the scientific research "The method of identifying a person by the iris using a neural network approach at the stages of segmentation and the formation of a feature representation".


The research uses an open dataset MMU Iris Database [1] provided by Multimedia University.

The dataset contains 450 images of the eyes of 45 people. There are 10 images for each person. In this case, the first five images are images of the right eye, the second five images are images of the left eye.

To implement the stage of iris segmentation using a neural network approach and subsequent assessment of the quality of segmentation, ground-truth segmentation masks are necessary. In this regard, we performed manual segmentation of the entire data set using Photoshop.

The data structure in the repository is as follows:
`Dataset` 
```
├──── images/
    ├──── 1/
       ├──── left/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
       ├──── right/
          ├──── 1.png
          ├──── 2.png
          ├──── ...
          └──── 5.bmp
    ├──── 2/
       ├──── left/
          ├──── 1.bmp
          ├──── 2.bmp
          ├──── ...
          └──── 5.bmp
       ├──── right/
          ├──── 1.png
          ├──── 2.png
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
          ├──── 1.png
          ├──── 2.png
          ├──── ...
          └──── 5.bmp
```

# Links

||Link|
|:------:|:-----------:|
|1|http://pesonna.mmu.edu.my/ccteo/|

