# Intelligent-Safety-Driving-Vechicle

# Abstract

The project aims to build a autonomous vehicle prototype which can autonomously navigate through a track by detecting lanes and centering itself between them. Many existing algorithms like lane detection, obstacle detection are combined together to provide the necessary control to the vehicle. Object tracking algorithms based on color, shape is used for tracking lanes. Based on the information retrieved, data/signals will be transferred to the controller, which will control the movement. This project uses OpenCV library for digital image processing.

# Steps

1. Initially, starting from capturing the frames from the driving environment.
2. Then converting the captured image frame from RGB to Grayscale. 
3. From the converted gray scale image, obtaining information about region of interest.
4. From the region of interest, we find lane and lines of roads.
5. From the lanes and lines data train the model.
5. Recording these sets of data and from this recorded sets of data the vehicle drives on its own.


# Conclusion

This project uses artificial intelligence technique for tracking and detection of the lanes. The camera elevation angle and position and illumination affects in the algorithm used for detecting lanes. The core of the project is a neural network, which is trained using  images of the "road" ahead and user input. At run time, the same images are used to activate the neural network, and the resulting action is executed on the robot. While a simple vision-based system cannot be expected to perform flawlessly but acceptable performance is achived through this intellige selfty driving vehicle.
