# Image_Compresion_kmeans

In this exercise, you will apply K-means to image compression.

In a straightforward 24-bit color representation of an image 2 , each pixel is represented as three 8-bit unsigned integers (ranging from 0 to 255) that specify the red, green and blue intensity values. This encoding is often refered to as the RGB encoding. Our image contains thousands of colors, and in this part of the exercise, you will reduce the number of colors to 16 colors. By making this reduction, it is possible to represent (compress) the photo in an efficient way. Specifically, you only need to store the RGB values of the 16 selected colors, and for each pixel in the image you now need to only store the index of the color at that location (where only 4 bits are necessary to represent 16 possibilities). In this part, you will use the K-means algorithm to select the 16 colors that will be used to represent the compressed image
