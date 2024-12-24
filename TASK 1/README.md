# Keylogger using `pynput`

This project is a simple keylogger built using Python and the `pynput` library. It captures and logs keyboard inputs to a file named `keylog.txt`.

## Features

- Logs all key presses, including special keys (e.g., `space`, `enter`, etc.).
- Saves the captured keystrokes to a text file (`keylog.txt`).
- Stops logging when the `Esc` key is pressed.

## Requirements

- Python 3.x
- `pynput` library

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/GokulCSECS/Prodigy-InfoTech
   cd Prodigy-InfoTech/TASK 1
   ```

2. Install the required library:
   ```bash
   pip install pynput
   ```

## Usage

1. Run the script:
   ```bash
   python keylogger.py
   ```

2. The script will start logging keystrokes into `keylog.txt`.

3. To stop the keylogger, press the `Esc` key.

## File Structure

```
.
├── keylogger.py   # The main script
├── keylog.txt     # The file where keystrokes are logged
└── README.md      # Project documentation
```

## Disclaimer

This project is for educational purposes only. Use it responsibly and only on systems you own or have explicit permission to test. Unauthorized use of this software may violate local, state, or federal laws.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve this project.

