# EVA4Phase2_Session2

**Dataset:**

Each group is supposed to collect 1000 Images for a class of Images (FlyingBirds, LargeQuadCopters, SmallQuadCopters, WingedDrones)
**Total Number of Images Collected and Processed:** 21633

**Sample Images:**

**FlyingBirds**

![FlyingBirds](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Sample%20Images/FlyingBirds.png)

**LargeQuadCopters**

![LargeQuadCopters](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Sample%20Images/LargeQuadCopters.png)

**SmallQuadCopters**

![SmallQuadCopters](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Sample%20Images/SmallQuadCopters.png)

**WingedDrones**

![WingedDrones](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Sample%20Images/WingedDrones.png)


| Class | Number of Images |
| :---------------- | :----------------: |
| FlyingBirds | 8333 |
| LargeQuadCopters | 4130 |
| SmallQuadCopters | 3621 |
| WingedDrones | 5549 |

- **Train and Validation Split:** 
70:30 that will give 15143 images for training (train) and 6490 images for testing/validation (val)

- **Image Resize Strategy:** 
GIMP – GNU Image Manipulation Program for resizing images into 224 * 224 without cropping or altering the image and to convert all images to JPEG

- **Overall Test / Validation Accuracy:** *84.72 (25 Epochs), 84.61 (20 Epochs)*

- **Model:** 
MobileNet V2 Model (Pretrained model from torch) we take and train the model according to our 4 classes of images (4 features classifier).

**MobileNet V2 Architecture:**

**Features:**

***Inverted Residuals - the inverted block has far fewer parameters:***
With inverted residual blocks, we do the opposite and squeeze the layers where the skip connections are linked. This hurts the performance of the network. The authors introduced the idea of a linear bottleneck where the last convolution of a residual block has a linear output before it’s added to the initial activations.

![MobileNet](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/MobileNet%20Architecture.png)

**Dataset Link:**


**PYNB Files:**

**25 Epochs**

![25 Epochs](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Session2_MobileNet_Acc_84_72(25_epochs).ipynb)


**20 Epochs**

![20 Epochs](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Session_2_Assignment_Acc_84_61(20_epochs).ipynb)

**Resizing Strategy:**

We have used GIMP Image Editor tool to resize the images and to convert all images to JPEG. Used BIMP for GIMP to perform batch manipulation of Images

**Model Used:**

Mobilenet V2 Model (Pretrained model from torch) we take and train the model according to our 4 classes of images (4 features classifier).

**Accuracy vs Epochs Graphs for Train and Test Curves:**

Overall Test / Validation Accuracy: *84.72 (25 epochs), 84.61 (20 epochs)*

**Training and Testing Accuracy:**

![Training and Testing Accuracy](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Train%20and%20Validation%20Accuracy.png)


**Training and Testing Loss**

![Training and Testing Loss](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Train%20and%20Validation%20Loss.png)

**Misclassified Images:**

**FlyingBirds:**

![FlyingBirds](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Misclassified%20Images%20-%20FlyingBirds.png)

**LargeQuadCopters:**

![LargeQuadCopters](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Misclassified%20Images%20-%20LargeQuadCopters.png)

**SmallQuadCopters:**

![SmallQuadCopters](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Misclassified%20Images%20-%20SmallQuadCopters.png)

**WingedDrones:**

![WingedDrones](https://github.com/srilakshmiv14/EVA4Phase2_Session2/blob/master/Misclassified%20Images%20-%20WingedDrones.png)
