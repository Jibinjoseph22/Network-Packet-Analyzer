
# Advanced Network Packet Analyzer

An intuitive and advanced tool for capturing and analyzing network packets in real-time. This tool is designed to help users inspect network traffic by monitoring packets and displaying detailed information, including IP addresses, protocols (TCP/UDP), and port numbers. Built using **Tkinter** for the GUI and **Scapy** for packet sniffing, this tool is ideal for network analysis and educational purposes.

## Features

- **Real-time Packet Capture**: Captures and analyzes packets in real-time.
- **Protocol Detection**: Detects and displays information about TCP and UDP protocols.
- **Packet Saving**: Ability to save captured packet details in a text file.
- **Start/Stop Capture**: Allows you to start and stop the packet capture at any time.
- **New Capture Section**: Start a fresh capture section without closing the application.
- **Clean GUI**: User-friendly graphical interface with color-coded text and status labels.

## Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)
- Scapy (`pip install scapy`)

## Installation

### Windows

1. Ensure you have Python installed. If not, download and install it from [Python's official site](https://www.python.org/).
2. Open a command prompt and install Scapy:
   ```bash
   pip install scapy
   ```
3. Download or clone the repository:
   ```bash
   git clone https://github.com/Jibinjoseph22/Network-Packet-Analyzer.git
   ```
4. Navigate to the project directory:
   ```bash
   cd Advanced-Network-Packet-Analyzer
   ```
5. Run the application:
   ```bash
   python packet_analyzer.py
   ```

### Linux

1. Open a terminal and ensure Python 3 is installed:
   ```bash
   sudo apt update
   sudo apt install python3
   ```
2. Install Tkinter and Scapy:
   ```bash
   sudo apt-get install python3-tk
   pip install scapy
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/Jibinjoseph22/Network-Packet-Analyzer.git
   ```
4. Navigate to the project directory:
   ```bash
   cd Advanced-Network-Packet-Analyzer
   ```
5. Run the application:
   ```bash
   python3 packet_analyzer.py
   ```

## Usage

- **Start Capturing**: Click the "Start Capturing" button to begin real-time packet sniffing.
- **Stop Capturing**: Click "Stop Capturing" to halt the packet capture process.
- **Save Packets**: After stopping the capture, you can save the captured packets to a text file.
- **Start New Section**: Clear previous data and start a new capture session without restarting the application.

## Contributing

Feel free to contribute by creating issues, requesting features, or submitting pull requests.

## License

This project is licensed under the MIT License.

