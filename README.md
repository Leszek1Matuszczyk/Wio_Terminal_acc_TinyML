# Wio_Terminal_acc_TinyML
A simple example of an AI model created using Edge Impulse, capable of detecting gestures using the built-in Wio Terminal accelerometer.


## Overview

Welcome to the "WIO_Terminal_acc" project, an Arduino-based solution for gesture detection using the Wio Terminal hardware. This project leverages the built-in accelerometer to detect various types of gestures, including:

- Shake
- Turn
- Wave
- Idle

This repository includes two essential libraries:

1. **Seeed_Arduino_LCD-master.rar**: A library for controlling the display on the Wio Terminal.
2. **Leszek_Akcelerometr_AI_inferencing.rar**: A custom library for AI model inferencing and gesture detection.

An example of the working project can be found on [YouTube](https://www.youtube.com/shorts/s8x7-IZCm6M).

## Hardware Requirements

Before you get started, you'll need the following hardware components:

- [Wio Terminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html): The primary hardware platform for detecting gestures.

## Library Installation

To make this project work, you need to install the necessary libraries:

1. Download the `Seeed_Arduino_LCD-master.rar` and `Leszek_Akcelerometr_AI_inferencing.rar` files from their respective sources.

2. Extract the contents of each RAR archive to a temporary directory using your preferred archive utility (e.g., WinRAR or 7-Zip).

3. Locate your Arduino Libraries folder, which is typically found in your Arduino installation directory.

4. Create two new folders for each library, naming them the same as the RAR file (without the ".rar" extension). Move the contents of the extracted folders into their respective library folders.

   - `Seeed_Arduino_LCD-master.rar` should be extracted to a folder named `Seeed_Arduino_LCD-master`, placed in your Arduino Libraries directory.

   - `Leszek_Akcelerometr_AI_inferencing.rar` should be extracted to a folder named `Leszek_Akcelerometr_AI_inferencing`, also placed in your Arduino Libraries directory.

## Getting Started

Now that you've installed the libraries, it's time to get started:

1. Open the `WIO_Terminal_acc.ino` Arduino sketch.

2. In the Arduino IDE, select the Wio Terminal board and the corresponding port to which your Wio Terminal is connected.

3. Upload the sketch to your Wio Terminal.

4. Run the project on the Wio Terminal to detect various gestures.

## License

This project is open-source and licensed under the [Apache License 2.0](LICENSE).

---

*Note: Don't forget to replace 'wio_terminal_image.jpg' with an image of your actual Wio Terminal or another relevant illustration in your README.*

For a live example, check out the [YouTube video](https://www.youtube.com/shorts/s8x7-IZCm6M).

For more information, visit our [GitHub repository](https://github.com/Leszek1Matuszczyk/Wio_Terminal_acc_TinyML).

Happy coding!

