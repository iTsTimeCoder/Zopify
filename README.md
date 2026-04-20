# 🟦 Zopify v1.0
**Zopify** is an open-source, lightweight compression engine built in C++. It aims to provide a fast and transparent way to archive data with a classic, distraction-free Windows interface.

![Zopify Logo](logo.png)

## 🌟 Key Features
- **Fast Compression:** Uses optimized RLE/Huffman-inspired logic for text and data.
- **Classic UI:** Designed with the timeless Windows Classic look for maximum performance on all hardware.
- **Open Source:** Built for the community as an ongoing charity (**Sadaqah Jariyah**).
- **Portable:** Single executable file with no heavy dependencies.

## 📸 Screenshots
![Engine Status](https://your-image-link-here.com/status.png)
*Zopify Engine running successfully on Windows.*

## 🚀 Getting Started
### Prerequisites
- A Windows machine (Tested on HP ProBook 650 G1).
- MinGW or Zig compiler (for building from source).

### How to Build
To compile the core engine into a Windows executable using Zig:
```bash
zig c++ main.cpp -target x86_64-windows-gnu -o Zopify.exe
```

🛠️ Roadmap
[x] Core Compression Engine.

[x] Windows CLI Executable.

[ ] Win32 API Classic Graphical Interface.

[ ] Support for multiple file formats.

🤝 Contributing
Contributions are welcome! If you have ideas to improve the compression ratio or the UI, feel free to fork this repo and submit a Pull Request.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

Built with passion by iTsTimeCoder. Dedicated as an Ongoing Charity (Sadaqah Jariyah) for the benefit of the global developer community.
