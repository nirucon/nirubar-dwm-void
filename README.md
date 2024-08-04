# nirubar-dwm-void

**nirubar-dwm** is a customizable status bar script for Void Linux and [dwm](https://dwm.suckless.org/), a lightweight window manager. This script provides a clean and informative status bar by displaying various system metrics and tools, tailored to enhance your workflow.

## Dependencies
- xsetroot
- Font Awesome (optional, for better icon support)
- `nmcli`, `iw`, `iwconfig`, or `wpa_cli` for WiFi status
- `free`, `df`, `date` commands

## Features
- Display RAM usage
- Display disk usage for the root filesystem
- Display current date and time
- Display battery status (if available)
- Display WiFi status (if available)

## Functionality

- **Font Awesome Check**: The script checks if Font Awesome is installed for better icon support.
- **Laptop Detection**: Checks if the device is a laptop by looking for battery directories.
- **WiFi Card Check**: Checks if a WiFi card is available.
- **RAM Usage**: Displays the current RAM usage.
- **Disk Usage**: Displays the disk usage of the root filesystem.
- **Date and Time**: Displays the current date and time.
- **Battery Status**: Displays the battery status, including charging status and capacity.
- **WiFi Status**: Displays the WiFi connection status using the detected network manager.
- **Status Bar Update**: Updates the status bar every minute with the collected system information.

## Installation

1. **Clone the Repository**: Clone this repository to your local machine.
    ```sh
    git clone https://github.com/nirubar-dwm-void/
    ```

2. **Make the Script Executable**:
    ```sh
    chmod +x nirubar-dwm-void/nirubar-dwm-void
    ```

3. **Edit `dwm` Configuration**: Add the script to your `dwm` configuration to run it at startup.

## Usage

1. **Run the Script**: Execute the script in the background. You can add it to your `.xinitrc` or similar startup file.
    ```sh
    ./nirubar-dwm/nirubar-dwm-void &
    ```

2. **Configure Modules**: Customize what is displayed on your status bar by commenting or uncommenting relevant modules in the script.


## License

Feel free to use and modify, donate if you want :) https://www.paypal.com/paypalme/nicklasrudolfsson
