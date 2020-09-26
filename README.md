# Automated-IoT-Photon-Car


Code created for the Automated IoT Photon Car project


Motor/Car code and hardware worked on by Ryan Roberts


Color sensor code and hardware worked on by Mansour Savadogo

The intent of this project was to create a car that automated its operation with regard to color inputs that it might see at a stoplight. The way we went about doing this was to
combine the functionality of a color sensor with the operation of two motors. When the color sensor saw something that was green, the motors would turn on. Likewise, the motors
turned off whenever they saw something that was red. The way this was done was with two Particle Photons. One was responsible for the color sensor input and output while the other
was responsible for operating the car itself. The two Photon devices communicated with one another via Particle events. The color sensor would read in whatever it was seeing and 
relay that information to the car Photon. The car Photon would then interpret that information and decide what to do with the motors from that. See the code itself for a more 
in-depth look at the functionality of the system. 
