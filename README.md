# **Image Enhancement with OpenCV DNN**

This Mini Python code does some image super resolution using DNN in OpenCV. Trying out LapSRN and EDSR with Traditional methods just for the heck of it.
## 🚀 Key Features
- Uses OpenCV's DNN module for image enhancement
- Supports EDSR and LapSRN models
- Can upscale images up to 8x higher resolution
- Saves upscaled images for comparison
- Includes example usage and output images
## 📚 Libraries Used
- OpenCV
- cv2
- dnn_superres
- CUDA for faster processing(Requires NVidia Graphics)
## 💻 Usage
*The main steps are:*
- Initialize DNN super resolution object
- Read pre-trained enhancement model
- Set model type and upscale factor
- Read input image
- Upscale image with DNN
- Save upscaled image
- Compare with bicubic upscaling

## 📸 Example Images
**Input	Image**:

![test](https://github.com/prxshetty/Super-Resolution/assets/72728788/52946dbf-8cd5-4b53-8dea-5443d9fa9a46)

**4x Upscaling with EDSR Method 1:**

![upscaled_test](https://github.com/prxshetty/Super-Resolution/assets/72728788/6f8d05f7-c371-464f-8847-2fab5135a4db)

**4x Upscaling with EDSR Method 2:**

*Added in REPO(File too large)*

**8x Upscaling with LapSRN:**

*Added in REPO(File too large)*

***Comparison of Input with UpScaled Image using LapSRN:***

<img width="1512" alt="image" src="https://github.com/prxshetty/Super-Resolution/assets/72728788/482c1370-d22c-4744-a8a1-bea10fcbb5dd">

