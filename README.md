# Arduino Temperature Logger

![Demo](link_to_demo_screenshot.png)

## Overview

This PyQt5-based application reads temperature data from an Arduino connected via USB and provides real-time visualization using pyqtgraph. The temperature data is displayed on an LCD widget, plotted on a graph, and logged in a table.

## Features

- Start and stop logging temperature data.
- Real-time visualization of temperature data using pyqtgraph.
- Logging of temperature data in a table.
- Responsive user interface.

## Prerequisites

- Python 3.x
- PyQt5
- pyqtgraph
- pyserial

1. Install dependencies:

pip install -r requirements.txt

2. Run the application:

python main.py

3. Connect Arduino via USB, click "Start Logging" to begin data collection, and use the "Stop Logging" button to end the process.

4. Configuration
Adjust the update interval, threshold temperature, and other parameters directly in the source code.

Contributing
Feel free to contribute by submitting bug reports, feature requests, or pull requests. Your feedback is highly appreciated!

