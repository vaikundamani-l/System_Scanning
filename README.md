# Browser Deep Scan – Digital Mirror

A client-side browser fingerprinting and system analysis tool that reveals what information websites can detect about your device, network, and hardware.

This project demonstrates how modern browsers expose system details such as IP address, GPU renderer, screen resolution, network information, and device fingerprints through JavaScript APIs.

The tool helps users understand their digital footprint and privacy exposure on the web.

---

## Live Demo

Open the project:

https://vaikundamani-l.github.io/System_Scanning/

---

## Project Overview

Websites can collect significant information about users without explicit permission.  
This project analyzes and displays those details in a clean dashboard interface.

The scan is performed entirely in the browser and no data is stored on any server.

---

## Features

### Network Information
- Public IP Address detection
- Connection type detection
- Estimated download speed
- Network latency (RTT)

### Device Fingerprinting
- Operating system platform
- CPU logical cores
- Canvas fingerprint hash
- Browser user-agent string

### GPU & Graphics Analysis
- WebGL vendor detection
- GPU renderer identification
- Graphics fingerprinting

### Display Information
- Screen resolution
- Window size
- Color depth
- Screen orientation

### Power & Hardware
- Battery level detection
- Charging status
- Estimated device memory (RAM)

### Locale Information
- Browser timezone
- Language settings
- Optional GPS location detection

### Data Export
- Copy full scan report to clipboard
- Export scan results as JSON file

---

## Technologies Used

- HTML5
- Tailwind CSS
- JavaScript
- WebGL API
- Canvas API
- Navigator API
- Lucide Icons

---

## System Architecture

User Browser  
↓  
JavaScript Scanner Engine  
↓  
Network APIs / Navigator APIs / Canvas / WebGL  
↓  
Data Aggregation  
↓  
Dashboard Visualization  
↓  
Export / Copy Report

---

## Privacy Notice

This project runs entirely in the browser.

- No tracking
- No cookies
- No backend storage
- No user data collection

All detected information is displayed only locally on your device.

---

## Example Output

```json
{
  "network": {
    "ip": "203.xxx.xxx.xxx",
    "connectionType": "4G"
  },
  "device": {
    "platform": "Linux x86_64",
    "cores": "8 Logical Cores"
  },
  "graphics": {
    "vendor": "Intel Inc.",
    "renderer": "Intel Iris OpenGL"
  }
}
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/vaikundamani-l/System_Scanning.git
```

Open the project folder and run:

```
index.html
```

Or deploy using GitHub Pages.

---

## Educational Purpose

This project demonstrates concepts used in:

- Browser fingerprinting
- Web security analysis
- Privacy awareness
- Client-side data exposure
- Cybersecurity research

---

## Future Improvements

- WebRTC IP leak detection
- Font fingerprinting
- Audio fingerprinting
- Browser plugin detection
- Security risk scoring system

---

## Author

Vaikundamani L

GitHub:  
https://github.com/vaikundamani-l

---

## License

This project is intended for educational and research purposes.
