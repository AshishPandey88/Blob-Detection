# Blob-Detection

![image](https://user-images.githubusercontent.com/98158660/150569984-814438a9-6e36-4d8d-9a62-d1b5bab57091.png)
Laplacian of Gaussian (LoG)

image source:https://www.freepik.com
This is an example of application of morphological operations on an image using the concepts of 
1) Converting an image to Binary
2) Erosion and Dilution operations to bring out the key features in an image 
3) Blob detection on virus image


Scikit image provides a great literature and methodology of Blob detection
Below is the link
"https://scikit-image.org/docs/dev/auto_examples/features_detection/plot_blob.html"

Quoting from Scikit-image: 

"Blobs are bright on dark or dark on bright regions in an image."

There are 3 methodoligies to detect the Blobs in an image
1) Laplacian of Gaussian (LoG)- Most accurate but slowest
2) Difference of Gaussian (DoG)- Faster approximation of LoG
![image](https://user-images.githubusercontent.com/98158660/150570116-a52f5d78-eeaf-4633-92a9-686cae50382a.png)

3) Determinant of Hessian (DoH)- Fastest Method
![image](https://user-images.githubusercontent.com/98158660/150570138-5133c2d6-063e-4505-904e-58b5176977b8.png)

Some parameters passed in the blob functions-

1) min_sigma= keep this low to detect smaller blobs
2) threshold= keep this low to detect lower intensity blobs

Additional literature you can refer:
1) Image Processing — Blob Detection
"https://towardsdatascience.com/image-processing-blob-detection-204dc6428dd"
