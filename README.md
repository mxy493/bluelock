# bluelock
A python script to automatically lock screen when bluetooth device disconnected, or unlock screen when device reconnect again.

## Prerequisites

- A computer with a Bluetooth adapter.
- A Linux system (Ubuntu 20.04 LTS is recommended).
- Make sure bluetoothctl is installed.

## Usage

Add executable permission: `chmod +x bluelock`

Run:

- Press Alt + F2, then just run the script: `bluelock`.
- Open a terminal, then execute command: `nohup bluelock &`.

Stop: `killall -9 bluelock`.
