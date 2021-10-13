# several-feature-inversion-projects-python-
several feature-inversion projects (python). Deep-photo implementation using lucid library.
Included is the default inception model example, but I created a places365 version which I
have not seen anybody use with lucid.

features/changes:
1) I increased the iterations to produce more robust output. 
2) Original attribution cariature project was limited to 224 pixels, but this supports any size.
3) Batch processing ability is built in. You can use this for a series of video frames to create animation.
4) Organized the code better and fix some mild redundancies.

here is an example of the places365:

![Image of placest](https://i.ibb.co/H7Lb7FS/9999.png)

here is an example of the original inception:
![Image of incept](https://i.ibb.co/XxBJ35Z/8888.png)
the glossyness/shinyness can be reduced by finding the following line in the second code box and changing n_steps to 512
I was trying to create a watercolor-like filter, but You may want to have it sharper.
def feature_inversion(img=None, layer=None, n_steps=2000, cossim_pow=0.0):

You can dive quickly into the projects by running them online with the following links:

original inception colab:
https://colab.research.google.com/github/400lbhacker/several-feature-inversion-projects-python-/blob/main/Feature_Inversion_with_Lucid.ipynb

places365 colab:
https://colab.research.google.com/github/400lbhacker/several-feature-inversion-projects-python-/blob/main/caffe_Places365_feature_inversion_deepstyle.ipynb


github: https://github.com/400lbhacker

facebook: https://www.facebook.com/profile.php?id=100071896345565

gmail: josepherickson135@gmail.com

I would like to give thanks for the following article for getting me started: https://aimaker.co/how-to-become-fashion-designer-under-15-minutes-using-artificial-intelligence/
