## Codes for T15's project Image Super-resolution
----


### Dataset: [Large-scale CelebFaces Attributes (CelebA) Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  
  
### Modules:
- DCGAN Module: `DCGAN.py`   finished  
- Image procseeing module: `image_processing.py`  finished  
- training module: `train.py`  finished
- test module: included in `train.py`      finished  
- coordination module: `main.py`     finished  

### Run：
- put CelebA Dataset in `/dataset`  
- put your own test images in `/test_img` (number of test images should = batch_size(default 16))  
- to train the model run: `python main.py train`  
- to use your own image to test the model run: `python main.py test`   
- intermediate results are saved in `/train` 






### Test results (images downloaded from google.com):  
this model was trained on a GTX1080Ti for 4 hours, approximately 70,000 batches.

left: 16*16 input       
middle: model's output      
right: orignal image  

![test result](https://github.com/tangni31/tensorflow/raw/master/project%20code/test_img/test_result.png)