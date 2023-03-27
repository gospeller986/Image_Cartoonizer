## Image_Cartoonizer

Image Cartoonizer is a computer vision application that uses OpenCV (Open Source Computer Vision Library) to convert an input image into a cartoon-like representation.
This process involves several steps, including edge detection, color quantization, and image filtering. 

## Steps to process the Image : 

```The first step is edge detection, which involves identifying the edges of objects in the image. 
This is done using a technique called Canny edge detection, which involves applying a series of filters to the image to detect areas of high gradient.
``` 
```
The second step is color quantization, which involves reducing the number of colors in the image to create a more stylized cartoon-like appearance.
This is done using a technique called k-means clustering, which groups similar colors together.

```

```
The final step is image filtering, which involves applying a series of filters to the image to create a more stylized appearance.
This includes techniques such as bilateral filtering, which smooths the image while preserving edges, and median filtering, which removes noise from the image.
```

## Algorith Used : 
   K-means clustering: K-means clustering is a machine learning algorithm used for color quantization. 
   It groups similar colors together and reduces the number of colors in the image to create a more stylized cartoon-like appearance.

## Reducing the Noise in  the Image 
   Median filtering: Median filtering is a nonlinear filtering technique used to remove noise from an image.
   It replaces each pixel with the median value of its neighboring pixels.
   
## Summary 

Overall, the Image Cartoonizer application using OpenCV takes an input image and applies a series of computer vision 
techniques to create a stylized cartoon-like representation of the image.




Technology used : 
  Python Language , OpenCv library 
