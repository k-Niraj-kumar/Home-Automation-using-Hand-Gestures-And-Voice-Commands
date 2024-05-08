# Home Automation using Hand Gestures and Voice Commands

This project aims to provide a hands-free way to control home appliances using hand gestures and voice commands. It utilizes computer vision techniques with OpenCV and the cvzone library to detect hand gestures, and the Whisper speech recognition model to understand voice commands. The project also includes an Arduino Uno board to control the connected appliances.

## Summary
The home automation system combines computer vision and speech recognition techniques to provide a natural and intuitive way to control home appliances. By leveraging hand gesture detection and voice command recognition, users can interact with the system in a hands-free manner, enhancing convenience and accessibility.

The system is built using Python and OpenCV for computer vision tasks, the cvzone library for hand tracking and gesture detection, and the Whisper model for speech recognition. The recognized gestures and voice commands are then translated into instructions and sent to an Arduino Uno board, which is responsible for controlling the connected appliances, such as lights, fans, and TVs.

The project demonstrates the integration of various technologies, including computer vision, speech recognition, and hardware control, to create a seamless and intelligent home automation solution.

## Features
* Voice command recognition for turning appliances on/off
* Real-time hand tracking and gesture detection
* Integration with Arduino Uno for hardware control

## Requirements
* Python 3.x
* OpenCV
* cvzone
* PyFirmata
* SpeechRecognition
* pydub
* faster_whisper
* Arduino Uno board

## Installation

*  Clone the repository:
https://github.com/k-Niraj-kumar/Home-Automation-using-Hand-Gestures-And-Voice-Commands.github

* Install the required Python packages:  pip install -r requirements.txt

* Connect the Arduino Uno board to your computer.
* Update the comport variable in the code with the correct COM port number for your Arduino board.

## Usage

* Run the main Python script
* The program will start the hand gesture detection and voice command recognition.
* Use the following hand gestures to control the appliances:

  * One finger up: Turn on the first light
  * Thumb up: Turn off the first light
  * Two fingers up: Turn on the second light
  * Index and thumb up: Turn off the second light
  * Three fingers up: Turn on the third light
  * Index, middle, and thumb up: Turn off the third light


* To control the appliances using voice commands, say the following phrases:

  * "Turn on [appliance name]" (e.g., "Turn on light", "Turn on fan", "Turn on TV")
  * "Turn off [appliance name]" (e.g., "Turn off light", "Turn off fan", "Turn off TV")
  * "Turn off system" (to turn off all appliances)


## Contributing
* Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
## License
* This project is licensed under the MIT License.

## Acknowledgments

* OpenCV
* cvzone
* PyFirmata
* SpeechRecognition
* pydub
* faster_whisper


