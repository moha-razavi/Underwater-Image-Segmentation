* Underwater Image Semantic Segmentation (TensorFlow)
This project is a university graphics-course assignment focused on underwater image semantic segmentation. It uses TensorFlow, a U-Net architecture with a VGG16 backbone, and is trained for 30 epochs. During training, the model generates a visualized mask output at the end of every epoch to track learning progress. During training, the model saves predicted mask samples each epoch and compares it to original the image and the true mask, showing the segmentation quality improving over time.

*Dataset
The project uses the SUIM (Semantic Underwater Image Segmentation) dataset, which provides underwater images and corresponding segmentation masks.
Dataset link: https://irvlab.cs.umn.edu/resources/suim-dataset

*Features
- U-Net model with VGG16 backbone
- Simple data loading and preprocessing pipeline
- Mask visualization saved after each epoch
- Inference notebook
- Testing the trained model
- Contains an academic presentation file on marine image segmentation
