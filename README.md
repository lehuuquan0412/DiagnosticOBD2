# Diagnostic OBD2

## Overview
This project focuses on developing a **car diagnostic device** to interface with vehicle onboard systems using industry-standard protocols. The device leverages modern microcontroller technology to retrieve, process, and display vehicle diagnostic data, ensuring quick and accurate troubleshooting for automotive systems.

## Features
- **OBD-II Protocol Support**: Communicates with a wide range of vehicles.
- **Real-Time Data Retrieval**: Displays live data streams such as engine RPM, speed, and sensor readings.
- **Error Code Management**: Reads and clears Diagnostic Trouble Codes (DTCs).
- **Compact Design**: Portable and user-friendly device casing.
- **Wireless Connectivity**: Supports 4G for remote operation.
- **Mobile App Management**: A dedicated smartphone app for device control and data monitoring.
- **Expandable**: Allows for additional sensors and custom functionalities.

## Hardware Requirements
- **STM32**: Microcontroller for wireless communication and data processing.
- **SIM7600 Module**: Provides cellular connectivity using the PPP stack.
- **OBD-II Adapter**: Interfaces with the car's diagnostic port.
- **Power Source**: 12V to 5V converter for powering the device.

## Software Stack
- **Firmware**: Developed using the RT-Thread framework for STM32.
- **Communication Protocols**: Supports UART and CAN for data exchange.
- **Mobile Application**: A Flutter-based app for extended monitoring and control.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-diagnostic-device.git
   ```
2. Configure the environment:
   - Set up the development environment for STM32 (e.g., STM32CubeIDE).
   - Install RT-Thread and necessary dependencies.
   - Connect the hardware components as per the schematic provided.
3. Build and flash the firmware:
   ```bash
   # Use your IDE or CLI tools to compile and upload the firmware to STM32.
   ```
4. Test the device using a compatible car and OBD-II adapter.

## Usage
1. Connect the device to the car's OBD-II port.
2. Power on the device using the car's power supply or an external source.
3. Use the Flutter-based mobile app or built-in interface to:
   - View live data.
   - Retrieve and clear DTCs.
   - Perform custom diagnostics.
   - Manage device settings via the app.

## Future Enhancements
- Integration with cloud services for data logging and analysis.
- Support for additional diagnostic protocols (e.g., UDS, J1939).
- Enhanced user interface with touchscreen support.

## Contribution
We welcome contributions from the community! Feel free to open issues, suggest features, or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

*Designed and developed by [quan04122002/OBD2Dev]*
