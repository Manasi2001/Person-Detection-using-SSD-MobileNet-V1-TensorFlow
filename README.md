# Human Detection using SSD MobileNet V1 (TensorFlow)

For object detection, a huge number of bounding boxes spanning the full image are made. Visual features are then extracted for each of the bounding box. They are evaluated and it is determined that which objects are present in the boxes. At the end, overlapping boxes are combined into a single bounding box and various objects are detected.

*Here, I used a model that was pretrained on the COCO dataset.*

**Step-1:** Imported necessary libraries and cloned various pretrained models.

**Step-2:** Installed the TensorFlow Object Detection API. 

**Step-3:** Loaded the model. Arranged the path of the test images. 

**Step-4:** Added functions to loop through all images, detect frames according to classes in them.

**Step-5:** Performed object detection on test images.

![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/ac161e843a76b2bbb6450e71d0bc5521/image.png)
![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/2c1a66d0b4711c474b98e4ff774400b4/image.png)
![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/b8b40f36eb8f99c286a9b8e604eedf31/image.png)

As it can be seen, only people are getting detected.

**Step-6:** Testing it on a new, random picture.

![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/f3a8bd87216fe3edb57c6c77c507e05b/image.png)

### Check out the notebook [here](https://colab.research.google.com/drive/1oBP_9iEnBrYDQjRHb-zhpUCeLXQwl7OV?usp=sharing).
