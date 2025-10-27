# Bluetooth_car
An Arduino-based RC car controlled wirelessly using any Bluetooth-enabled smartphone. The project utilizes the HC-05 Bluetooth module to establish a serial communication link. Motor driver L298N is used to control the speed and direction of four DC motors.

## 🤖 Hardware Connections

### Motor Driver (e.g., L298N)

* **Left Motor (Motor 1):**
    * **Arduino Pin 5 (PWM)** -> Enable Pin (ENA)
    * **Arduino Pin 2** -> Input 1 (IN1)
    * **Arduino Pin 3** -> Input 2 (IN2)
* **Right Motor (Motor 2):**
    * **Arduino Pin 6 (PWM)** -> Enable Pin (ENB)
    * **Arduino Pin 4** -> Input 3 (IN3)
    * **Arduino Pin 7** -> Input 4 (IN4)

### Bluetooth Module (HC-05)
* **Arduino Pin 0 (RX)** -> HC-05 Module **TX** (Transmit) Pin
* **Arduino Pin 1 (TX)** -> HC-05 Module **RX** (Receive) Pin
