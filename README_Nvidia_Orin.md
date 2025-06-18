# Quanser SDK for Linux on Nvidia Jetson Orin
The *Quanser SDK for Linux on Nvidia Jetson Orin* supports the following Quanser devices:
- [Quanser Qube-Servo 3](https://www.quanser.com/products/qube-servo-3/)
- [Quanser QUBE Servo 2 - USB](https://www.quanser.com/products/qube-servo-2/)
- [Quanser AERO](https://www.quanser.com/products/quanser-aero/)
- [Quanser QArm Mini](https://www.quanser.com/products/qarm-mini/)


If using a Nvidia Jetson Orin Nano board (as on the [Quanser QBot Platform](https://www.quanser.com/products/qbot-platform/)) and installing the *Quanser SDK for Linux on Nvidia Jetson Orin* for the very first time on that target, execute the following commands: 
```
wget --no-cache https://repo.quanser.com/debian/release/config/configure_qbot_platform_repo.sh
chmod u+x configure_qbot_platform_repo.sh
./configure_qbot_platform_repo.sh
rm -f ./configure_qbot_platform_repo.sh
```

If using a Nvidia Jetson AGX Orin board (as on the [Quanser QCar 2](https://www.quanser.com/products/qcar-2/)) and installing the *Quanser SDK for Linux on Nvidia Jetson Orin* for the very first time on that target, execute the following commands: 
```
wget --no-cache https://repo.quanser.com/debian/release/config/configure_qcar2_repo.sh
chmod u+x configure_qcar2_repo.sh
./configure_qcar2_repo.sh
rm -f ./configure_qcar2_repo.sh
```


To install *Quanser SDK for Linux on Nvidia Jetson Orin*, or upgrade an existing installation, run the following commands:

```
sudo apt update
sudo apt-get install quanser-sdk
```


To uninstall and remove *Quanser SDK for Linux on Nvidia Jetson Orin*, run the following command:

```
sudo apt-get --auto-remove purge quanser-sdk
```

