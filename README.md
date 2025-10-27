# Bluetooth_car
An Arduino-based RC car controlled wirelessly using any Bluetooth-enabled smartphone. The project utilizes the HC-05 Bluetooth module to establish a serial communication link. Motor driver L298N is used to control the speed and direction of four DC motors.

Motor Driver Connections
The code defines six pins to control two motors, likely through a motor driver IC like an L298N
1. Arduino Pin 2 to Input 1 (e.g., IN1) 
2. Arduino Pin 3 to Input 2 (e.g., IN2) 
3. Arduino Pin 5 to Enable Pin (e.g., ENA) 
4. Arduino Pin 4 to Input 1 (e.g., IN3) 
5. Arduino Pin 7 to Input 2 (e.g., IN4) 
6. Arduino Pin 6 to Enable Pin (e.g., ENB) 
7. Arduino Pin 0 (RX) to HC-05 Module TX (Transmit) Pin
8. Arduino Pin 1 (TX) to HC-05 Module RX (Receive) Pin
