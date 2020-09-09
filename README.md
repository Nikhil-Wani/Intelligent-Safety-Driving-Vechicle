# Intelligent-Safety-Driving-Vechicle

# Abstract

The project aims to build a autonomous vehicle prototype which can autonomously navigate through a track by detecting lanes and centering itself between them. Many existing algorithms like lane detection, obstacle detection are combined together to provide the necessary control to the vehicle. Object tracking algorithms based on color, shape is used for tracking lanes. Based on the information retrieved, data/signals will be transferred to the controller, which will control the movement. This project uses OpenCV library for digital image processing.

# Steps

Initially, starting from capturing the frames from the driving environment.

Then converting the captured image frame from RGB to Grayscale. 

From the converted gray scale image, obtaining information about edges of the path and to detect objects (obstacles) in front of the vehicle.

From the edges of the path detected and the objects captured training the vehicle accordingly using Neural network.

Recording these sets of data and from this recorded sets of data the vehicle drives on its own.
