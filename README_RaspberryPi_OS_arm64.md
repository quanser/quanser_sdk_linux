# Quanser SDK for Raspberry Pi OS (64-bit)
The *Quanser SDK for Raspberry Pi OS (64-bit)* supports the following Quanser devices:
- [Quanser Qube-Servo 3](https://www.quanser.com/products/qube-servo-3/)
- [Quanser QUBE Servo 2 - USB](https://www.quanser.com/products/qube-servo-2/)
- [Quanser AERO](https://www.quanser.com/products/quanser-aero/)
- [Quanser QArm Mini](https://www.quanser.com/products/qarm-mini/)
- [Quanser Mechatronic Actuators Trainer](https://www.quanser.com/products/mechatronic-actuators-trainer/)
- [Quanser Mechatronic Sensors Trainer](https://www.quanser.com/products/mechatronic-sensors-trainer/)

To setup a supported Raspberry Pi with Raspberry Pi OS (64-bit), follow the official [Raspberry Pi OS (64-bit)](https://www.raspberrypi.com/software/operating-systems/) instructions to install the operating system.

To install the *Quanser SDK for Raspberry Pi OS (64-bit)* for the very first time on that target, execute the following commands: 
```
wget --no-cache https://repo.quanser.com/debian/release/config/configure_raspbian64_repo.sh
chmod u+x configure_raspbian64_repo.sh
./configure_raspbian64_repo.sh
rm -f ./configure_raspbian64_repo.sh
```


To install *Quanser SDK for Raspberry Pi OS (64-bit)*, or upgrade an existing installation, run the following commands:

```
sudo apt update
sudo apt-get install quanser-sdk
```


To uninstall and remove *Quanser SDK for Raspberry Pi OS (64-bit)*, run the following command:

```
sudo apt-get --auto-remove purge quanser-sdk
```

