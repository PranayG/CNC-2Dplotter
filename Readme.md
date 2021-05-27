# CNC-2Dplotter

CNC 2D Plotter is a project designed to draw a specific diagram on paper by giving the commands from the computer. It uses a software called Inkscape which allows us to draw vector graphics on the computer and then generates a G-code.  The axes is controlled by two stepper motors, one which controls the movement along y-direction which moves the central limb. The second stepper controlled the movement along x-direction by moving the pen holding plate. The pen movement for drawing is controlled by the servo motor in the up-down direction. It is controlled by a GRBL controller. GRLB is the open source firmware freely available for every one and is used as a firmware for the CNC machine. GRBL shield and GRBL firmware is best for 3 axis stepper CNC machine. The CNC shield is placed over the Arduino board.

The project uses 3D printed PLA parts and GT2 pulleys and belts. 

![image](https://user-images.githubusercontent.com/9202531/119230554-ba647400-bb2d-11eb-8dc4-81393fc10b54.png)

Working of the Project :

Step1 : Uploading MIGRBL library code to Arduino Uno

![image](https://user-images.githubusercontent.com/9202531/119230847-fb10bd00-bb2e-11eb-8f89-ddb2f1df21e4.png)

Step2 : Connecting Servo motor to GRBL CNC shield.
![image](https://user-images.githubusercontent.com/9202531/119230953-92761000-bb2f-11eb-804e-e469a4b4c654.png)

Step3 : Generating G-code using Inkscape.

Step4: Running the code from controller.
![image](https://user-images.githubusercontent.com/9202531/119231059-fb5d8800-bb2f-11eb-89b8-b8f05c6622c0.png)


LINKS:

GRBL - https://github.com/grbl/grbl

Arduino - https://www.arduino.cc/
