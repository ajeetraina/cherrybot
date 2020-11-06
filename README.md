# CherryBot - A Payload Delivery Robot

A proposal for an autonomous robot system for use as a swag delivery in the conferences as well as food delivery in university campuses that is capable of terrestrial as well as aerial locomotion.Our goal is to build the so-called “CherryBot Systems” which is a swag delivery robot equipped with production-ready System on Module(SOM) NVIDIA Jetson Nano board which is just 70 x 45mm , a low-powered AI deployed as Edge device, a sensor suite that includes multiple cameras, GPS and  swappable batteries. It is an autonomous delivery robot which picks up and delivers swags  and food items within a conference, campus or a roughly 5-6 square kilometers area centered around university premises. The goal is to allow the robot to traverse a given conference and campus area delimited by coordinates on a GPS receiver, detect and avoid obstacles in its path, thereby distributing swags and food items using Deep Learning algorithm. 

The project involves both hardware and software development. In the hardware part we will 
leverage robotic components, both in terms of aerial as well as terrestrial locomotion. 
The software part will involve developing an encrypted QR code generator which runs inside the Docker container and  detects the QR code sign to deliver the package.

Testing will be done continuously and in stages. We will first develop and test the hardware components and the communications. The second stage will be to integrate a navigation algorithm with obstacle avoidance to enable the robot to move autonomously. The final stage will be to incorporate a mapping software running inside Docker containers on top of NVIDIA Jetson Nano that will distribute the swags based on QR code.

  
## Technical Details

The CherryBot system uses deep learning to correctly interpret data gathered from its sensors and to make intelligent decisions that ensure a fast, safe and cost efficient delivery. It can correctly identify objects or people or detect objects and obstacles to avoid collisions in a safe reliable manner.

In a conference, these bots are used to carry swags from each booth to deliver items to the end-user. It has a large compartment to hold deliveries equivalent to the size of two grocery bags with a maximum weight of 5 kilograms. It’s like a mini-mart. The vehicle appears large enough to accommodate small and medium-sized parcels, Robots that transport small packages from shops or local distribution centers directly to consumers. The CherryBot system is capable of transforming between the two modes of locomotion at will through the transformable mechanism, allowing the robot to overcome large obstacles in their mission environment. 

## How does it work?

- The delivery robot first picks up swags from respective conference booths.
- These delivery robot hold compartments where all various swags are placed
- Once the robot arrives close to conference attendees, the compartment is opened once QR code is scanned by the end-user.
- The conference pass holder uses QR code to unlock the flap and pick the swags
- The robot senses that the swag have been collected
- It continues to the next conference attendees


The Bill of Material (BOM) for this project work have been listed in Appendix- A1
	



