# Intelligent-Safety-Driving-Vechicle

# Abstract

The project aims to build a autonomous vehicle prototype which can autonomously navigate through a track by detecting lanes and centering itself between them. Many existing algorithms like lane detection, obstacle detection are combined together to provide the necessary control to the vehicle. Object tracking algorithms based on color, shape is used for tracking lanes. Based on the information retrieved, data/signals will be transferred to the controller, which will control the movement. This project uses OpenCV library for digital image processing.

# INTRODUCTION

A self-driving vehicle, which is also called  as  intelligent vehicle or robot vehicle an autonomous vehicle capable of fulfilling the human transportation capabilities of a traditional vehicle. Self-driving vehicles are vehicles that can drive through traffic all by themselves. As unbelievable or far-fetched as it may sound, it may just be the greatest technological revolution of the near future

With the rapid increase of urban traffic, the traffic safety becomes more and more important. According to the research, many accidents of roadway departure crashes are caused by driver inattention. A System called Lane Departure Warning System (LDWS) being capable of warning the driver when the vehicle begins to move out of its lane is desperately needed to eliminate these crashes. Lane detection is a kernel part in LDWS and also key technology for the successful development and employment of that system. In the past few years, several approaches for lane detection were proposed and successfully demonstrated.

An camera is installed in a vehicle facing to the road in front of the vehicle to capture a sequence of road/scene images for analyzing the driving situation. The situation includes the distance to a front obstacle or vehicle, the speed of the vehicle, and the left/right location of the vehicle in a road lane.
Initially teaching the robot how to drive; this is done by making the vehicle go around a track a small number of times. The image data, along with the user action is used to train a Neural Network. At run-time, images capture by camera of what is in front of the vehicle are fed into the neural network and the appropriate driving action is selected. 
With the number of accidents increasing day by day, it has become important to take over the human errors.  All of this could come to an end with self-driving vehicles and then let the passengers continue with their work. This will avoid not only accidents but also bring a self-relief for minor day to day driving activities.

#Steps

Initially, starting from capturing the frames from the driving environment.

Then converting the captured image frame from RGB to Grayscale. 

From the converted gray scale image, obtaining information about edges of the path and to detect objects (obstacles) in front of the vehicle.

From the edges of the path detected and the objects captured training the vehicle accordingly using Neural network.

Recording these sets of data and from this recorded sets of data the vehicle drives on its own.
