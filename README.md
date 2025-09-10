# 📱 IPQR 🖥️

[![PyPI version](https://img.shields.io/pypi/v/ipqr?style=flat-square)](https://pypi.org/project/ipqr/)
[![Python](https://img.shields.io/pypi/pyversions/ipqr?style=flat-square)](https://pypi.org/project/ipqr/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![PyPI downloads](https://img.shields.io/pypi/dm/ipqr?style=flat-square)](https://pypi.org/project/ipqr/)
[![GitHub stars](https://img.shields.io/github/stars/kasundularaam/ipqr?style=flat-square)](https://github.com/kasundularaam/ipqr/stargazers)

IPQR is a cross-platform command-line tool that generates QR codes for your local server URLs. It automatically detects your local IP address and creates a QR code that can be scanned to quickly access your local server from mobile devices. No more typing long IP addresses on your phone! 🚀

## 🌟 Features
- 🔍 Automatic local IP detection
- 🎨 ASCII QR code generation
- 🔢 Custom port support
- 🚀 Easy to use command-line interface
- 🐧 Cross-platform support (Windows, macOS, Linux)

## 🛠️ Installation
You can install IPQR easily using pip:
```
pip install ipqr
```
This works on Windows, macOS, and Linux!

## 🚀 Usage
### Basic Usage
To use IPQR with the default port (8000):
```
ipqr
```
### Custom Port
To specify a custom port:
```
ipqr -p 5000
```
or
```
ipqr --port 5000
```

## 📖 Example
Here's what you'll see when you run IPQR:
```
$ ipqr
Local server URL: http://192.168.1.100:8000
Scan this QR code to access the local server:
███████████████████████████████
███████████████████████████████
████ ▄▄▄▄▄ █ █ █▀█▄█ ▄▄▄▄▄ ████
████ █   █ █▄█▀██▀ █ █   █ ████
████ █▄▄▄█ █▀█ █▀██  █▄▄▄█ ████
████▄▄▄▄▄▄▄█ █ ▀ █▄█▄▄▄▄▄▄▄████
████  ▀▄██▄▀▀▀█▄▀▀ █▄█▀ ▀▄▀████
████▀▀▀██▀▀▄▀ ▀▀▀▀ ▀█▀  ▀█▀████
████ ▀▄▀▀▄▄▀▀▀██▀▀▀█▀▀▄▀▀▄ ████
████▄██▄▄▄▄▀▀▀▄█ ▄▀▄▀▄▄▄▀▀▄████
████ ▄▄▄▄▄ █▄█▀ ▀▄█ █ █▄█ █████
████ █   █ █  █▀▀▄▀▀█▄  ▄▀█████
████ █▄▄▄█ █▀█ █▀▀ █▄█▄▀███████
████▄▄▄▄▄▄▄█▄███▄█▄██▄██▄██████
███████████████████████████████
███████████████████████████████
```
Just scan the QR code with your mobile device, and you're good to go! 📱✨

## 🐧 Linux Users
IPQR is fully compatible with Linux systems! It uses smart IP detection methods that work across different Linux distributions. If you encounter any issues, please report them on our GitHub page.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/kasundularaam/ipqr/issues). 

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements
- Thanks to the creators of [qrcode](https://github.com/lincolnloop/python-qrcode) and [netifaces](https://github.com/al45tair/netifaces) libraries.
- Inspired by the need to quickly share local server addresses during development.

## 🚀 About the Author
Created with ❤️ by Kasun Dulara. Connect with me on [GitHub](https://github.com/kasundularaam).

Happy coding! 💻✨
