# SSH Brute Forcing Script (Credential Stuffing)

## Disclaimer
This code is intended for **educational and awareness purposes only**. It is crucial to obtain proper authorization and comply with all relevant laws and regulations before using this tool. Misuse of this tool can result in legal consequences.

## Introduction
This SSH Brute Forcing Script is a proof of concept designed to demonstrate the methodology and impact of credential stuffing attacks against SSH servers. It is meant for cybersecurity professionals and students to understand and mitigate such threats.

## Features
- **Interactive CLI**: Guided user experience for ease of use.
- **Multi-threading Support**: Enhanced efficiency with asynchronous operations.
- **Rate Limiting and Timeout Handling**: Improved reliability against various SSH configurations.
- **Extensive Logging**: Detailed reports on script activities for analysis.
- **Safe Testing Mode**: Restricts operations to predefined IP ranges for safe practice.

## Installation
1. Clone the repository: `git clone https://github.com/davidbombal/ssh_bruteforcing.git`
2. Create a virtual environment: `python -m venv sshbruteforcer_env`
3. Activate the virtual environment:
   - Windows: `source ./sshbruteforcer_env/Scripts/activate`
   - Unix/Mac: `source ./sshbruteforcer_env/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`

## Usage
Run the script with the command: `python ssh_bruteforcer.py`
Follow the interactive CLI prompts to configure and start the attack simulation.

## Configuration
Users can specify settings in `config.ini` to customize the tool without altering the code.

## Testing and Quality Assurance
- Comprehensive unit and integration tests ensure reliability.
- Tested for compatibility with various SSH server configurations.

## Contributing
Contributions are welcome! Please read our contribution guidelines for more information on how to report issues, submit patches, and more.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Thanks to the cybersecurity community for continuous support and contributions.
