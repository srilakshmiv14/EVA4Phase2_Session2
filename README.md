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

- **Overall Test / Validation Accuracy:** *84.72 (25 epochs), 84.61 (20 epochs)*

- **Model:** 
Mobilenet V2 Model (Pretrained model from torch) we take and train the model according to our 4 classes of images (4 features classifier).
