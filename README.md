# IP Subnet Calculator

> Advanced subnet calculator with network splitting capabilities

[![Live Demo](https://img.shields.io/badge/demo-online-green)](https://mustafazeya.github.io/subnet-calculator/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🌟 Features

- **CIDR Calculator** - Calculate network details from CIDR notation
- **Network Splitting** - Split networks into smaller subnets using multiple methods:
  - By number of subnets
  - By hosts per subnet  
  - By target subnet mask
- **Network Classification** - Automatic classification (Class A/B/C, Private/Public)
- **Copy to Clipboard** - One-click copy for all results
- **Dark/Light Mode** - Toggle between themes
- **Real-time Calculations** - Instant results as you type

## 🚀 Live Demo

Visit the live calculator: [https://mustafazeya.github.io/subnet-calculator/](https://mustafazeya.github.io/subnet-calculator/)

## 📖 Usage

1. Enter a CIDR block (e.g., `192.168.1.0/24`)
2. View instant calculations including:
   - Network and broadcast addresses
   - Usable IP range
   - Subnet mask and wildcard mask
   - Total and usable hosts
3. Use the subnet splitter to divide the network into smaller subnets

## 🛠️ Development

```bash
# Clone the repository
git clone https://github.com/mustafazeya/subnet-calculator.git
cd subnet-calculator

# Open in browser
open index.html
```

## 📝 Examples

**Standard Private Network:**
```
192.168.1.0/24
→ 254 usable hosts
```

**Large Corporate Network:**
```
10.0.0.0/16
→ 65,534 usable hosts
→ Can be split into multiple /24 subnets
```

**Small Point-to-Point Link:**
```
172.16.0.0/30
→ 2 usable hosts (perfect for router-to-router links)
```

## 🎨 Theme

Designed to match the [mustafazeya.github.io](https://mustafazeya.github.io) design system:
- Dark theme by default
- IBM Plex Sans & JetBrains Mono fonts
- Blue/purple accent colors
- Modern card-based UI

## 📄 License

MIT License - feel free to use this project for any purpose.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📧 Contact

Created by [Mustafa Zeya](https://github.com/mustafazeya)
