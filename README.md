## *READ AND WRITE AN IMAGE* ##



## **AIM**
To write a python program using OpenCV to do the following image manipulations.i) Read, display, and write an image. ii) Access the rows and columns in an image. iii) Cut and paste a small portion of the image.

Software Required:

Anaconda - Python 3.7
__
## Algorithm: ##
## Step1: ##

Choose an image and save it as a filename.jpg

## Step2: ##

Use imread(filename, flags) to read the file.

## Step3: ##

Use imshow(window_name, image) to display the image.

## Step4:  ##

Use imwrite(filename, image) to write the image.

## Step5: ##


End the program and close the output image windows.

_


# *PROGRAM*
_
### Program: Read and Write

### Developed By: Eluru Ganesh
### Register Number: 212220230016

_
*i) # To Read,display the image*

  python
  import 
  cv2.imshow('color image',color_image)
  gray_image=cv2.imread('x.jpg',0)
  cv2.imshow('color image',color_image)
  cv2.imshow('grayimage',gray_image)
  cv2.waitKey(0)

  

**ii) #To write the image**
    
   
   `python
    cv2.imwrite('x.jpg',gray_image)
  `



*iii) #Find the shape of the Image ``python3*
python
   print(color_image.shape)

iv) #To access rows and columns
python3
   python
   import random
for i in range(100):
    for j in range(color_image.shape[1]):
        color_image[i][j]= [random.randint(0,255),random.randint(0,255),random.randint(0,255)]

    import matplotlib.pyplot  as plt
plt.imshow(color_image[200:670,200:670])



**v) #To cut and paste portion of image**

python
tag=color_image[300:400,300:400]
color_image[50:150,50:150] =tag
plt.imshow(color_image)

```

## *OUT PUT*:
**i) Read and display the image**



__![Image Link](https://github.com/veerapallijanith/Read-and-Write-Image/blob/main/jan1.jpeg)__


__![Image Link](https://github.com/veerapallijanith/Read-and-Write-Image/blob/main/jan2.jpeg)__

*ii)Write the image*

__![Image Link](https://github.com/veerapallijanith/Read-and-Write-Image/blob/main/jan2.jpeg)__


*iii)Shape of the Image*

__![Image Link](https://github.com/veerapallijanith/Read-and-Write-Image/blob/main/jan3.jpeg)__

*iv)Access rows and columns*

__![Image Link](https://github.com/veerapallijanith/Read-and-Write-Image/blob/main/jan4.jpeg)__



*v)Cut and paste portion of image*



## *Result:*

Thus the images are read, displayed, and written successfully using the python program
