# Pet Status Tracker

An Android app in Kotlin to monitor your pet's temperature and movement status in real-time via Bluetooth connection to an ESP-32 device.

## Features
- Scan and connect to ESP-32 via Bluetooth (Classic SPP or BLE)
- Real-time display of temperature and movement (Running, Walking, Rest)
- Card-style UI with color-coded states
- Alerts for high temperature
- Timestamp for last update
- MVVM architecture with ViewModel and StateFlow
- Android 12+ Bluetooth permissions

## How to Build
1. Open the project in Android Studio or VS Code with Android extensions.
2. Build the project using Gradle.
3. Run on a device with Bluetooth enabled.

## Permissions
- Bluetooth (scan, connect)
- Location (required for Bluetooth scanning)

## Notes
- ESP-32 must send data in the format:
  ```
  TEMP: 32.5
  MOVE: Running
  ```
- Replace placeholder icons and assets as needed.

## License
arahan-codes
