-Project Description
This project explores the application of the K-means clustering algorithm for image compression. By reducing the number of unique colors in an image, we can significantly compress its size while maintaining a visual representation close to the original. The K-means algorithm groups similar colors together, replacing each pixel's color with the nearest cluster center. The project demonstrates the effect of using different numbers of clusters (K) on the image, showcasing how varying levels of compression can balance between file size and image quality.

Features
Efficient Image Compression:

The project uses K-means clustering to reduce the number of colors in an image, which directly results in compression.
Different levels of compression can be achieved by varying the number of clusters (K), allowing for customization based on the desired balance between image quality and file size.
Visual Comparison:

The project provides a visual comparison of the original image with compressed versions at different levels (K=8, 16, 32).
This feature helps in understanding the impact of color reduction on the visual quality of the image.
No Loops Implementation:

The image processing and clustering operations are implemented without using loops, leveraging vectorized operations in NumPy for better performance.                                             
