# GL-MVP1
## Auto Annotation using Meta's Segment Anything Model

## INTRODUCTION

This project utilizes Meta's Segment Anything Model to perform image segmentation based on user-selected points. The process involves converting an image to the HWC format, generating a mask for the selected point, extracting the mask's boundary coordinates, and plotting these coordinates on the image.

## FEATURES

- Load and preprocess an image in HWC format.
![image](https://github.com/user-attachments/assets/b0987a9c-f893-4b4b-b326-187968e52646)


- Generate a segmentation mask for a user-selected point.

![image](https://github.com/user-attachments/assets/9443a5c5-1303-477a-a241-82ff247e852c)


- Extract boundary coordinates of the mask using OpenCV.
  ![image](https://github.com/user-attachments/assets/ab1a1e40-8a9c-49cf-92a1-d369e479e55e)


  
- Visualize the mask boundaries on the original image with Matplotlib.
  ![image](https://github.com/user-attachments/assets/6173db55-eacc-47df-8f30-b15cc31beb22)



