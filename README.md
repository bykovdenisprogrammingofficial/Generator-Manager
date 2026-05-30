# PassWorld Manager

A secure password generator and manager application built with Python, Tkinter, and CustomTkinter.

## Features

- 🔐 **Password Generator**: Create strong, customizable passwords
- 💾 **Password Manager**: Securely store and manage your passwords
- ⚙️ **Settings**: Customize themes, language, and generation parameters
- 🌐 **Multi-language Support**: English and Russian
- 🎨 **Modern UI**: Built with CustomTkinter for a beautiful interface
- 🔒 **Privacy First**: All data stored locally with encryption

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/passworldmanager.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python src/main.py
   ```

## Building Executable

To create a standalone executable:

```bash
pyinstaller --onefile --windowed src/main.py
```

The executable will be created in the `dist` folder as `passworldmanager.exe`.

## Usage

1. On first launch, review and accept the Privacy Policy
2. Use the Password Generator tab to create secure passwords
3. Save passwords to the Password Manager tab
4. Organize and search your saved passwords
5. Customize appearance and behavior in Settings

## Security Notes

- All passwords are encrypted locally using AES-256 encryption
- Master password is required to access the password manager
- No data is transmitted over the internet
- Application uses industry-standard cryptography libraries

## License

MIT License

## Privacy Policy

See [PRIVACY_POLICY.txt](PRIVACY_POLICY.txt) for details.
