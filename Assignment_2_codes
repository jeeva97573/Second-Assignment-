### python codes for reading, displaying, plotting a histogram and smoothing of a brain image 

#import statement blocks
import numpy as np 
import matplotlib.pyplot as plt
import scipy
from scipy import misc,ndimage

#read the image into an array 
brain_image=plt.imread(‘Brain.jpg’)

#exhibit the class of the image 
type(brain_image)

#draw the image
plt.imshow(brain_image)   

#creating a title for the image 
plt.title(‘Reading a Brain Image’)

#show the image 
plt.show()

#exhibit the size of the image
print(brain_image.shape)

#draw the image as reverse greyscale colormap 
plt.imshow(brain_image,cmap=‘Greys_r’)

#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(brain_image, bins=10)

#show the image
plt.show()

#using a specific gaussian kernel for smoothing
first_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=5)
#draw the image as reverse greyscale colormap
plt.imshow(first_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(first_smoothed_image, bins=10)
#show the image
plt.show()

#using a specific gaussian kernel for smoothing
second_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=10)
#draw the image as reverse greyscale colormap
plt.imshow(second_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(second_smoothed_image, bins=10)
#show the image
plt.show()

#using a specific gaussian kernel for smoothing
third_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=20)
#draw the image as reverse greyscale colormap
plt.imshow(third_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(third_smoothed_image, bins=10)
#show the image
plt.show()

#using a specific gaussian kernel for smoothing
fourth_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=30)
#draw the image as reverse greyscale colormap
plt.imshow(fourth_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(fourth_smoothed_image, bins=10)
#show the image
plt.show()

#using a specific gaussian kernel for smoothing
fifth_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=40)
#draw the image as reverse greyscale colormap
plt.imshow(fifth_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(fifth_smoothed_image, bins=10)
#show the image
plt.show()

#using a specific gaussian kernel for smoothing
sixth_smoothed_image=scipy.ndimage.gaussian_filter(brain_image, sigma=50)
#draw the image as reverse greyscale colormap
plt.imshow(sixth_smoothed_image, cmap=‘Greys_r’)
#show the image 
plt.show()

#plot a histogram of the image 
plt.hist(sixth_smoothed_image, bins=10)
#show the image
plt.show()
