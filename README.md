
# Introduction #

We are the Kanaan team from the Qabatiya Directorate of Education of the State of Palestine.  We designed, assembled and programmed the robot, which we called Caesar, to perform the tasks and performance required in preparation for participation in the World Robotics Olympiad (WRO) competition.

The vehicle CAESAR is designed using two microcontrollers: Raspberry Pi, and Arduino. The Arduino is programmed on a Linux environment, which is installed on Raspberry pi, Arduino is connecting to the Raspberry Pi using a serial port, and the platform that is used for programming and uploading the code on Arduino is Arduino IDE ARM version.

Depending on the previous, the C++ language is used for Arduino, and the Python language is used for Raspberry pi, the C++ language is used to program the Arduino microcontroller, to control the movement of the motor, steering wheel, and sensors (Ultrasonic, gyroscope), while the python is used for image processing depending on the suitable library so that the Open CV library has been downloaded suitable to python. it is used for processing the image coming from the camera, clustering the red and green pillars, and sending commands for each case according to the color.

In a deeper look, the code is discussed in detail.
