# Faster R-CNN

The repository contains code for object detection on the Pascal VOC dataset using [Faster R-CNN](https://arxiv.org/pdf/1506.01497.pdf). 

The pretrained weights can be found [here](https://drive.google.com/file/d/1EUcjFZNp1BAHF2UwlzGgJ_43v9CPmlBC/view?usp=sharing). Please replace the empty weights file in the `weights` folder with the downloaded file (~535 MB).

`test.ipynb` contains code for testing the model. A sample image is placed under the `images` directory. Simply run all the cells of this notebook to test the model. Here's a sample result:

![man_horse](https://i.imgur.com/HjJ4ULM.png "Testing Faster R-CNN")

The repository also contains an extension of Faster R-CNN for instance segmentation ([Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf)).
