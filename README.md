# Drawaria PyMacroRecord

**Drawaria PyMacroRecord** is a Python-based macro recorder and playback tool designed to automate repetitive tasks on your computer. It captures mouse movements, clicks, scrolls, and keyboard inputs, allowing you to replay them with precision. This tool is ideal for automating workflows, testing, or simplifying repetitive actions.

---

## Features

- **Mouse and Keyboard Recording**: Capture mouse movements, clicks, scrolls, and keyboard inputs.
- **Playback with Customization**: Replay recorded macros with adjustable speed, repeat intervals, and scheduled playback.
- **Save and Load Macros**: Save your recorded macros to a file and load them later for playback.
- **Customizable Settings**: Configure recording and playback behavior through a settings file.
- **Minimization Options**: Minimize the application during recording or playback for uninterrupted workflow.
- **Post-Playback Actions**: Automatically perform actions like standby, log off, shutdown, or restart after playback.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Drawaria-PyMacroRecord.git
   cd Drawaria-PyMacroRecord
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**:
   ```bash
   python main.py
   ```

---

## Usage

1. **Recording**:
   - Click the "Record" button to start recording your actions.
   - Perform the mouse and keyboard actions you want to automate.
   - Click the "Stop" button to end the recording.

2. **Playback**:
   - Click the "Play" button to replay the recorded macro.
   - Adjust playback settings (speed, repeat, etc.) in the settings menu.

3. **Saving and Loading**:
   - Save your recorded macro to a file for future use.
   - Load a previously saved macro to replay it.

---

## Configuration

The application uses a configuration file (`settings.ini`) to customize behavior. You can modify settings such as:

- **Recording Options**: Enable/disable mouse movements, clicks, and keyboard inputs.
- **Playback Options**: Set playback speed, repeat intervals, and scheduled playback.
- **Minimization Options**: Minimize the app during recording or playback.
- **Post-Playback Actions**: Configure actions like standby, shutdown, or restart after playback.

---

## Requirements

- Python 3.x
- Libraries: `pynput`, `tkinter`

---

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Support

If you encounter any issues or have suggestions, please open an issue on the [GitHub repository](https://github.com/yourusername/Drawaria-PyMacroRecord/issues).

---

**Happy automating!** 🚀