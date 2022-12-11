# AUTOMATIC-BUILDING-DETECTION-USING-VERY-HIGH-RESOLUTION-SATELLITE-IMAGERY

Building conclusions from remotely sensed images is a difficult and costly undertaking
using traditional approaches. Knowing the location of buildings is critical in issues
such as population estimation, city planning, and disaster management. The extraction
of building inferences by manpower is a time-consuming and repeated job. It is
vulnerable to major human-caused mistakes. Diversity in building geometries,
variations in reflectance values, and comparable qualities with other objects remain
weak with index-based and traditional machine learning algorithms, therefore building
inferences are always an issue to address for remote sensing. Deep learning-based
techniques, which have recently gained popularity, appear to be promising. Deep
learning-based techniques began to be deployed in practice, leaving the theoretical
realm, particularly in light of hardware and software improvements. The Unet and
Deeplabv3+ architectures are the most often used for determining building inferences
in the context of semantic segmentation. The goal of this research is to autonomously
recognize buildings by combining Unet and Deeplabv3+ architectures with Resnet50,
Resnet101, and Efficient-b1 encoders. The study made use of the Massachusetts
building dataset. Six distinct models were trained in total. With U-Net and Deeplabv3+
architectures, Resnet50, Resnet101, and Efficient-b1 encoders, and the same
hyperparameters, these models were extended to 80 epochs. The models trained with
U-Net perform better; the model with the highest IoU score is 87.42 percent IoU, and
it was trained with U-Net using the resnet101 encoder. Again, two additional models
were trained using U-Net by experimenting with different encoders, and as a
consequence of this training, resnet50 earned an IoU score of 86.66 percent, while the
model utilizing the Efficient-b1 encoder achieved an IoU score of 86.65 percent. When
we visually assess the model output achieved with the Efficient-b1 encoder, we
observe that it is far too poor to deserve this score. This might be due to a mismatch
between the model and the encoder. While Deeplabv3+ models performed worse than
U-Net, the model trained with the resnet101 encoder earned IoU scores of 86.16
percent, resnet50 86.03 percent, and Efficient-b1 81.94 percent.
