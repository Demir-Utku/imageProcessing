# Image Processing
1. Import the necessary packages (imutils and cv2)
2. Load the image and show its dimensions                                                                                                                                                                                                                                                                                            
Note: Images are represented as a multi-dimensional NumPy array with shape:                                                         
                   no. rows (height) * no. columns (width) * no. channels (depth)                                              
3. Display the image - click the window
4. Access the RGB pixel at x=50, y=100
5. Extract a 100 * 100 pixel square ROI - starting at x=320, y=60, ending at x=420, y=160
6. Resize the image to 200 * 200 pixel ignoring the aspect ratio
7. Resized width is 300 pixel
8. Calculate aspect ratio with the help of imutils library
9. Rotate the image by 45 degrees using OpenCV or rotate via imutils library
10. Apply a Gaussian blur with a 11 * 11 kernel to the image to smooth it
11. Draw a 2 pixel thich rectangle surrounding the face and blue 20 pixel circle at x=300, y=150
12. Draw a 5 pixel thick red line from x=60, y=20 to x=400, y=200
