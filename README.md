Semantic Segmentation of High Voltage Power Line Insulator Images

Abstract

Insulators in high-voltage power supply lines are one kind of the most important equipment for seamless power supply. Defected or dirty insulators can cause power supply disruption. Therefore, it is very important to maintain insulators proper functioning. Maintenance of insulators manually by human intervention for identifying faulty or dirty insulators and then repairing or replacing them is costly, time consuming, laborious and risky. To automate this process, we present deep learning based methods for semantic segmentation of insulators using a synthetic dataset because of lacking of enough real world insulator images. The segmented masks can be used for identifying faults or dirt in real-world later. We have used U-net with ResNet-34 backbone, U-net with ResNet-50 backbone, LinkNet with VGG16 backbone, LinkNet with VGG19 backbone, PSPNet with ResNet-50 backbone for the segmentation purpose. Among these LinkNet with VGG19 backbone has performed best achieving accuracy of 0.9972, Jaccard Index or IoU of 0.9626 and Dice Coefficient of 0.9803. The Dice Coefficient is approximately 3.19% better than previously published state-of-the-art Dice Coefficient for semantic segmentation on this dataset. Previously published state-of-the-art Dice Coefficient for semantic segmentation on this dataset is 0.95 which was achieved by LinkNet with VGG16 backbone. We have applied the best method for some real-world images also, but haven’t computed any metrics for them because of lacking of respective ground truth masks.

Authors

AL MUSABBIR
MSC in CSE, United International University, Dhaka, Bangladesh
BSC in CSE, North South University, Dhaka, Bangladesh
Email: almusabbir.rakin@gmail.com, al.musabbir@northsouth.edu, amusabbir2510010@mscse.uiu.ac.bd