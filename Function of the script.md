# SSH Brute Forcing Script

## Purpose of the Script
This script is designed to automatically try different combinations of usernames and passwords to establish an SSH (Secure Shell) connection with a server or computer system. SSH is a widely used protocol for secure network communication.

## Functionality

### Reading Username and Password Combinations
- The script reads username and password combinations from a file named `passwords.csv`.
- This file should contain various combinations for the script to try.

### Getting the Server's Address
- The user is prompted to input the IP address of the target server.
- An IP address is a unique identifier for a computer on the Internet or a local network.

### Attempting to Connect
- The script attempts to connect to the server using SSH for each username and password combination.
- It performs these attempts rapidly, one after another.

### Handling Success and Failures
- **Success**: If a combination successfully connects, the script records it in a file named `credentials_found.txt`.
- **Failure**: If a combination fails, the script moves on to the next one.
- **Rate-Limiting**: The script identifies if the server is limiting connection attempts to prevent this kind of access.

### Parallel Attempts
- The script employs 'threading' to make multiple connection attempts simultaneously, enhancing the speed of the process.

### Logging and Error Handling
- Features are in place to manage errors and log activities for troubleshooting. These are more technical aspects that support the script's primary function.

## Disclaimer
This script is intended for educational purposes only and does not promote any illegal activities. Users must adhere to ethical and legal standards while using or modifying this script.
