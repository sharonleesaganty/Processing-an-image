# Processing-an-image

**Project Description**

To process and manipulate images for object detection by performing operations such as resizing, grayscale conversion, and displaying the images. The goal is to explore image transformations and prepare data for advanced image analysis.

**OUTPUTS:**

**•	Image Download:**

The image is successfully downloaded and saved as image.jpg.

**•	Original Image Display:**

The original image is displayed from the numpy array.

**•	Image Resizing:**

The image is resized to 200x200 pixels and saved as image_resized.jpg.

**•	Grayscale Conversion:**

The image is converted to grayscale and saved as image_gray.jpg.

**•	Final Display:**

The original, resized, and grayscale images are displayed successfully

**PSEUDOCODE:**

**1. Download Image from URL**

    - Send HTTP request to the URL to fetch the image
    
    - If the request is successful:
    
        - Save the image to the local machine
        
    - Else:
    
        - Print an error message
        
**3. Display the Original Image**

    - Load the image using a display function

    - Show the image on the screen
    
**4. Convert Image to Numpy Array**

    - Read the image and convert it into a numpy array
    
    - Print the shape of the image (dimensions)
    
    - Display the image using a plotting library

**5. Resize the Image**

    - Open the image using a library
    
    - Resize the image to a new size (e.g., 200x200)
    
    - Save the resized image
    
    - Display the resized image
    
**6. Convert the Image to Grayscale**

    - Read the original image using OpenCV
    
    - Convert the image from RGB to grayscale
    
    - Save the grayscale image
    
    - Display the grayscale image

