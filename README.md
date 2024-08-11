# Arduino Data Logger with Python GUI

## Overview

This project involves an Arduino-based data logging system, accompanied by a Python program for real-time data visualization. The Python script utilizes PyQt5 for the graphical user interface (GUI) and pyqtgraph for plotting incoming data from the Arduino via a serial connection. This setup allows users to monitor sensor data in real-time through a convenient and interactive interface.

## Features

- **Real-time Data Visualization**: Displays data from the Arduino in real-time using a dynamic plot.
- **Serial Communication**: Connects to the Arduino via a serial port to read sensor data.
- **Interactive GUI**: Provides a user-friendly interface built with PyQt5.

## Requirements

- Python 3.x
- PyQt5
- pyqtgraph
- Arduino (with appropriate sensors connected)

## Installation

1. Clone the repository or download the ZIP file and extract it.

    ```bash
    git clone https://github.com/yourusername/arduino-data-logger.git
    ```

2. Navigate to the project directory.

    ```bash
    cd arduino-data-logger
    ```

3. Install the required Python libraries:

    ```bash
    pip install pyqt5 pyqtgraph pyserial
    ```

4. Ensure your Arduino is connected to your computer via a USB port.

## Usage

1. Upload the appropriate Arduino sketch to your Arduino device to begin data transmission. Ensure the serial baud rate in the Python script matches the baud rate in the Arduino sketch.
2. Run the Python script:

    ```bash
    python python-code.py
    ```

3. The GUI will open, and you should see real-time data being plotted on the graph.

## Project Structure

- **`python-code.py`**: The main Python script that runs the GUI and handles serial communication with the Arduino.
- **`improvements.txt`**: A text file containing suggestions for future improvements to the project.
- **`Final-Report.docx.pdf`**: A PDF document detailing the final report of the project.
- **`.gitignore`**: Specifies files and directories for Git to ignore.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## Acknowledgements

This project was developed to provide a simple yet effective method for real-time data visualization from an Arduino.
