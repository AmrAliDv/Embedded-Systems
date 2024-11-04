https://github.com/user-attachments/assets/985a28c3-6f19-46d8-9fe0-02db997a35e4

### FOTA (Firmware Over The Air) Project 
The FOTA (Firmware Over The Air) project aims to simplify and automate the firmware update process for embedded systems. 

### Key Features:
- Frontend Interface: The project includes a user-friendly web page built with HTML and JavaScript,
allowing users to easily initiate firmware updates through an intuitive interface.
- HTTP Protocol: Firmware files are transferred securely over the HTTP protocol,
ensuring compatibility with various web technologies and simplifying deployment.
- NodeMCU Server Mode: The NodeMCU is configured to operate in server mode, enabling it to wirelessly send firmware updates to connected devices.
This feature allows for efficient and flexible deployment of updates in various environments.
- UART Communication: The NodeMCU communicates with the Blue Pill microcontroller using UART (Universal Asynchronous Receiver-Transmitter), facilitating seamless data transfer and minimizing latency.
- Data Integrity Verification: To ensure the reliability of the updates, a Cyclic Redundancy Check (CRC) is implemented.
  This mechanism verifies the integrity of the transferred data, preventing issues that could arise from corrupted files.
