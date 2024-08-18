# 📱 IPQR 🖥️

IPQR is a magical ✨ command-line tool that generates QR codes for your local server URLs. It automatically detects your local IP address and creates a QR code that can be scanned to quickly access your local server from mobile devices. No more typing long IP addresses on your phone! 🚀

## 🌟 Features

- 🔍 Automatic local IP detection
- 🎨 ASCII QR code generation
- 🔢 Custom port support
- 🚀 Easy to use command-line interface

## 🛠️ Installation

You can install IPQR easily using pip:

```
pip install ipqr
```

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