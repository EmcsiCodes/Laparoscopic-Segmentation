# Laparoscopic-Segmentation

A PyTorch-based deep learning project for semantic segmentation of laparoscopic surgical images using the **CholecSeg8k** dataset. The objective is to assign a class label to every pixel in an image, allowing the model to distinguish between important surgical structures, regions, and tools. CholecSeg8k contains **8,080 annotated frames** extracted from **17 video clips**, with pixel-level labels for **13 classes**.

The segmentation classes include **black background, abdominal wall, liver, gastrointestinal tract, fat, grasper, connective tissue, blood, cystic duct, l-hook electrocautery, gallbladder, hepatic vein,** and **liver ligament**.

This repository is intended as a clean framework for **data preprocessing, model development, training, evaluation, and visualization**, with room for experimenting with **custom encoders** and different segmentation architectures in PyTorch. 