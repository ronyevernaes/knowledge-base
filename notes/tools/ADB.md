# ADB

## Share Phone Screen

- Connect the phone
- Execute: .\adb tcpip 5555
- Disconnect the phone
- At the phone, go to: Settings > My device > All specs > Status > IP address
- Execute: .\adb connect <ip>:5555
- Execute: .\scrcpy -s <ip>:5555