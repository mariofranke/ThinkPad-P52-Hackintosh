# ThinkPad P52 Hackintosh with Ventura OS

## Introduction
This repository provides configuration files and instructions to turn your ThinkPad P52 into a Hackintosh running Ventura OS. The Hackintosh configuration is based on the inspiration and work from the [ThinkPad-P52-Hackintosh](https://github.com/liuyishengalan/ThinkPad-P52-Hackintosh) repository.

## Progress Table

| Feature         | Status          | Notes                                      |
|-----------------|-----------------|--------------------------------------------|
| Webcam          | Working         |                                            |
| Audio           | Working         |                                            |
| Microphone      | Not Working     |                                            |
| Sleep           | Not Tested      |                                            |
| Battery         | Working         |                                            |
| Bluetooth       | Not Working     |                                            |
| Wi-Fi           | USB Dongle      | You may need to replace the Wi-Fi card.    |
| Graphics        | Not Tested      |                                            |
| Touchpad        | Not Tested      |                                            |
| Trackpoint      | Working.        |                                            |
| HDMI/DisplayPort| will not work   |                                            |
| USB Ports       | Working         |                                            |
| Ethernet        | Working.        |                                            |

## Getting Started

### Requirements
- ThinkPad P52 or similar model
- Ventura OS image
- OpenCore bootloader
- EFI configuration files (provided in this repository)

### Installation
1. Follow the instructions from the [ThinkPad-P52-Hackintosh](https://github.com/liuyishengalan/ThinkPad-P52-Hackintosh) repository to set up your initial Hackintosh environment.

2. Download the Ventura OS image and create a bootable USB.

3. Copy the EFI configuration files from this repository to the EFI partition of the bootable USB.

4. Boot from the USB and proceed with the Ventura OS installation.

### Post-Installation
1. After installing Ventura OS, mount the EFI partition of your system drive.

2. Copy the EFI configuration files from the USB to the EFI partition of your system drive.

3. Reboot your Hackintosh.

## Contributing
If you encounter any issues or have additional improvements, feel free to submit a pull request or open an issue.

## Credits
- [ThinkPad-P52-Hackintosh](https://github.com/liuyishengalan/ThinkPad-P52-Hackintosh) for the inspiration and initial setup.
- The OpenCore team for their excellent bootloader.

## Disclaimer
Please note that creating a Hackintosh may violate Apple's end-user license agreement (EULA). Use this configuration at your own risk, and I am not responsible for any data loss or damage caused to your hardware.

## License
This project is licensed under the [MIT License](LICENSE).