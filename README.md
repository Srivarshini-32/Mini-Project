# Mini-Project
Smart Automated Parking Barrier System
Smart Automated Parking Barrier System 🚗⚡
An Arduino-based smart parking system designed to automate vehicle entry, manage parking safety, and provide manual touch alerts. This system integrates multiple sensors and actuators to optimize parking lot management, reduce vehicle idling, and introduce an emergency alert system. 
⚙️ How It Works
Vehicle Detection (Entry): The Ultrasonic Sensor constantly monitors the entry range. When a car comes within the threshold, the Micro Servo rotates 90° to lift the barrier.
Status Indicators: While the gate opens, the LED lights up and the Buzzer emits a continuous sound to alert pedestrians and the driver.
Successful Parking (Exit/Secure): As the car moves forward into the spot, the front bumper triggers the IR Sensor mounted on the end wall. This signals a successful park, prompting the gate to close, and turning off both the LED and Buzzer.
optional touch (remote gate opening):when youtouch the touch sensor,the gate opens, the LED lights up and the Buzzer emits a continuous sound
