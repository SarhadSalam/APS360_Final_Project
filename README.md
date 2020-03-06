# APS360_Final_Project

Data Cleaning Process

Starting with trousers:
1. Get SHOP images with trousers (go through all items)
2. Make sure the items landmarks are all present (1 or 2) for every 3rd index and the viewpoints are no wear or frontal
3. Crop the image to the bounding box of the trouser
4. Use edge detection from OpenCV Canny to generate a "doodle" of the image
5. Resize the images to 100x200

