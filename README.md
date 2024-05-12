# Remote Controlled Car built using Arduino and controlled via Bluetooth

## Necessary Hardware Components

  1. Car Structure (1 board and 4 wheels)
  2. 4 DC Motors
  3. Switch
  4. 12v battery
  5. 6v battery
  6. Arduino Uno
  7. L298N Motor Driver
  8. Jumper Cables
  9. HC - 06 Bluetooth Module
  10. USB A to USB B cable

## Necessary Sofware Components

  1. Arduino Bluetooth RC Car Controller
  Download from here : https://github.com/rashintha/BluetoothRCCarController
  2. Arduino IDE
  Download from here : https://www.arduino.cc/en/software

## Step-by-step Instructions

  1. Download and install the Arduino IDE according to your operating system
  2. Connect the Arduino Uno with your computer using the USB A to USB B cable
  3. Download rc.ino (https://github.com/Shamsuzoha/arduino_rc_car/blob/main/rc.ino)
  4. Open the file, select your connected USB port from Tools>ports and arduino uno from Tools>boards
  5. Upload the file (ctrl+u)
  6. Power your Arduino by connecting your 5V battery with GND and 5V jacks. Keep a switch in the middle to make sure you can turn it off and on
  7. Connect the pins 9,10,11 and 12 with the L298N Motor Driver
  8. Connect your motor driver with the DC Motors and power them with the 12V battery
  9. Connect your motors with the wheel by maintaning the serial Below
        #### Arduino Pin 9  = Left Front Wheel
        #### Arduino Pin 10 = Right Front Wheel
        #### Arduino Pin 11 = Right Back Wheel
        #### Arduino Pin 12 = Left Back Wheel
  11. Set the entire thing on the board with glue or screws
  12. Install the Arduino Bluetooth Controller for Android on your phone


## Final Product

![367401437_820916496194766_6009519116089170031_n](https://github.com/Shamsuzoha/arduino_rc_car/assets/90334698/c84d5b8c-542c-4516-97e5-4d505eeedb7a)


