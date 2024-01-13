
# Smart Doorbell with Face Recognition and Telegram Integration

## Overview

Create a smart doorbell system that integrates face recognition technology with a Telegram notification system. The project uses an Arduino, a camera module, and an LCD display. When a visitor is detected, the system captures their face, recognizes whether they are a known face (e.g., the homeowner), and sends a notification to the homeowner on Telegram. The LCD display provides real-time feedback, and additional features such as an audible buzzer and LED indicator enhance the user experience. The integration of Python for face recognition and Arduino for hardware control results in a comprehensive and secure smart doorbell solution.

## Key Features

- **Face Recognition:** Utilizes OpenCV and Python for accurate face recognition.
- **Hardware Control:** Arduino-based control for LED, and LCD display.
- **Telegram Integration:** Sends instant notifications to the homeowner through Telegram by using Telegram Bot.
- **User Feedback:** LCD display offers real-time feedback on the system's status.
- **Security:** Differentiates between recognized faces (homeowner) and strangers.
- **Visual Alerts:** Includes a buzzer for audible notifications and an LED indicator for visual alerts.

## Components annd Hardware setup

- Arduino board.
- Camera module for face capture.
- LCD display for visual feedback with 12C module.
- LED indicator for visual alerts.
- Telegram bot for instant messaging.
  ![smartlock](https://github.com/EasyPeasyarduino/SmartLockUsingTelegram/assets/140818076/73ba95ef-c74c-4451-9640-f75df68c37b5)


## Usage

1. Clone the repository: `git clone https://github.com/EasyPeasyarduino/SmartLockUsingTelegram.git`
2. Install necessary dependencies for Python.
3. Connect the Arduino and upload the provided sketch.
4. Run the Python script for face recognition.
5. generate telegram Bot.

## Configuration

- Replace placeholders in the Arduino sketch and Python script with your specific details.
- Configure your Telegram bot and obtain the API token for integration.

## Additional Information

### Extensions

- **Cloud Storage:** Implement cloud storage for a face recognition database.
- **Home Automation:** Integrate with home automation systems for extended functionality.
- **Mobile App:** Develop a mobile app for remote monitoring and control.

## Conclusion

The Smart Doorbell project provides an intelligent and user-friendly solution for enhancing home security and convenience. The combination of face recognition technology and Telegram integration ensures that homeowners stay informed about visitors in real time.

Feel free to contribute, open issues, or suggest improvements!
