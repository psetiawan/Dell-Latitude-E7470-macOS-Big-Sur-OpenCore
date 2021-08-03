# Dell Latitude E7470 macOS Big Sur (OpenCore)

## Specification
- Model		Dell Latitude E7470
- Processor	Intel Core i5-6300U
- Graphics	Integrated Intel HD Graphics 520
- Memory		8GB 2133MHz DDR4 SODIMM
- Display		14" 1920 x 1080 (Full HD)
- Storage		256GB M.2 SSD
- WLAN 		Intel Dual Band Wireless-AC 8260
- Bluetooth	Intel 
- Camera		720p Webcam
- Soundcard	Realtek ALC293
- Keyboard	Backlit Keyboard
- Trackpad	ALPS Touchpad


## What's Working
- Intel HD 520 Graphics incuding graphics acceleration
- All USB ports
- Internal camera
- WiFi using AirportItlwm
- Bluetooth using IntelBluetoothFirmware and IntelBluetoothInjector
- Shutdown/ Reboot/ Sleep/ Wake
- Audio
- Intel Gigabit Ethernet
- iMessage, FaceTime, App Store
- Keyboard and Trackpad(two finger vertical swipes)
- SD Card Reader using Sinetek-rtsx

## What's Not Working
- Multitouch gestures for ALPS touchpad

##Current configuration
- macOS: Big Sur 11.5.1
- OpenCore: 0.7.2
- Audio AppleALC with boot-args alcid=11
- PowerManagement using CPUFriend BatterySaving (to reconfigure please use CPUFrindFriend)

#Credits
- Acidanthera
- Dortania
- adityabakare https://github.com/adityabakare/macOS-Dell-Latitude-E7470

