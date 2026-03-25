# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/fc8628c9-859d-4c6b-931a-41aca4840b90" />


### 2. Network Server – Recent Events

<img width="1906" height="1063" alt="image" src="https://github.com/user-attachments/assets/80dbf737-964c-4718-8512-a90d5c038f70" />

<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/6bf62bcd-a108-458b-b901-fdb931e4395f" />


### 3. Dashboard Command Sending

<img width="1914" height="970" alt="image" src="https://github.com/user-attachments/assets/f16d2e05-a3f8-4543-af9b-61eb1abf444d" />


### 4. Relay Status Dashboard Output

<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/2bee8c7c-d436-4b86-852d-7f8ca0c25a60" />


### Bulb ON → Relay ON  

<img width="1903" height="1059" alt="image" src="https://github.com/user-attachments/assets/9bcf1dc9-2e4f-4bae-aa96-b3a7a01304cc" />

### Bulb OFF → Relay OFF

<img width="1916" height="1085" alt="image" src="https://github.com/user-attachments/assets/ed51455f-04bb-4c14-9f19-357f73920ca9" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
