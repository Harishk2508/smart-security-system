# smart-security-system
# Security System with PIR Sensor and GSM Module

## Introduction

Welcome to the Security System project repository! This project aims to provide a guide and implementation for building a security system using a Passive Infrared (PIR) sensor and a GSM module with Arduino. The system detects motion using the PIR sensor and sends SMS alerts via the GSM module to notify users of any intrusions or unauthorized access.

## Features

- Motion detection using a PIR sensor.
- Real-time SMS alerts for detected motion.
- Customizable settings for sensitivity and alert recipients.

## Hardware Requirements

- Arduino Board (e.g., Arduino Uno)
- PIR Sensor
- GSM Module (e.g., SIM800L)
- SIM Card
- Jumper Wires
- Power Supply

## Software Requirements

- Arduino IDE
- Libraries for GSM module (e.g., SIM800L library)

## Setup Instructions

1. **Hardware Setup:** Connect the PIR sensor, GSM module, and Arduino board as per the provided instructions. Ensure proper power supply and connections.

2. **Development Environment:** Install Arduino IDE and any necessary libraries for the GSM module. Ensure that the correct board and port are selected in the Arduino IDE.

3. **Write Arduino Sketch:** Create the Arduino sketch to interface with the PIR sensor and GSM module. Implement logic to detect motion and send SMS alerts upon detection.

4. **Upload Sketch to Arduino:** Connect the Arduino board to your computer via USB and upload the Arduino sketch using the Arduino IDE.

5. **Test the System:** Power up the Arduino board and PIR sensor. Trigger motion in front of the PIR sensor and verify that SMS alerts are sent successfully via the GSM module.

## Additional Notes

- Customize SMS Message: Modify the Arduino sketch to customize the SMS message sent by the system.
- Security Settings: Adjust the sensitivity of the PIR sensor and configure alert recipients (phone numbers) as per your requirements.
- Power Supply: Ensure that the system has a reliable power supply to operate continuously.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

Special thanks to the Arduino community and contributors for their libraries and resources.

## Feedback

If you have any feedback, suggestions, or issues, please feel free to open an issue or contact the project maintainers.


