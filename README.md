# Port Scanner Application

## Project Description
Educational port scanning tool developed for network security course. Implements TCP connect scan with GUI interface.

## Features
- TCP port scanning (1-65535)
- Real-time results display
- Custom branding with base64 logo
- Built with ttkbootstrap (modern UI)

## Technologies
- Python 3.10+
- tkinter / ttkbootstrap
- socket (native)
- PIL for image processing

## Usage
- In terminal: python scanner.py
- Enter target IP (e.g., 127.0.0.1)
- Set port range
- Click SCAN
- View open ports in right panel

## License
- MIT License - for educational purposes only

## Author
- Joseph Avatiants
- Email: joavat2009@gmail.com
- GitHub: joavat-2009

## Installation

```bash
git clone https://github.com/joavat-2009/port-scanner-0.1.git
cd port-scanner-0.1
pip install -r requirements.txt
python scanner.py
