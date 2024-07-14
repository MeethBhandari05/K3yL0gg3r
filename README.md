# K3yL0gg3r
Keylogger featuring encrypted audio recording, screenshot capture, system information collection, and clipboard data retrieval for thorough system monitoring.


# Usage
1. Computer Information Collection:
Gathers system information including processor details, system version, machine type, hostname, and IP addresses (both private and public).

2. Clipboard Content Retrieval:
Copies the clipboard content and saves it to a file.

3. Microphone Recording:
Records audio through the microphone and saves it as an audio file.

4. Screenshot Capture:
Takes screenshots and saves them as image files.

5. Keylogger Functionality:
Logs keystrokes and saves them to a file.
Includes a timer to control the duration of logging.

6. File Encryption:
Encrypts collected data files using the Fernet encryption.

7. Email Sharing:
Sends the encrypted files via email to a specified address.



# Setup and Configuration
Prerequisites:

# Python environment with required libraries installed.
Internet connection for remote access and email functionalities.
(Optional) Virtual Private Server (VPS) for remote access installation.
Libraries:

# Install necessary Python libraries using the following command:
bash
Copy code
pip install -r requirements.txt
# Configuration:

Modify the configuration variables in the script as needed (e.g., email_address, password, file_path, etc.).


# Legal Disclaimer
This tool is intended for educational and ethical penetration testing purposes only. Unauthorized use of this tool to compromise computer systems without explicit permission from the owner is illegal and unethical. The developers are not responsible for any misuse or damage caused by this tool.


