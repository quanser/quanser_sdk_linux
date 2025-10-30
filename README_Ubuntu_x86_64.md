# Quanser SDK for Ubuntu on x86_64 platform
The *Quanser SDK for Ubuntu x86_64* (e.g., 64-bit Ubuntu PC) supports the following Quanser devices:
- [Quanser Qube-Servo 3](https://www.quanser.com/products/qube-servo-3/)
- [Quanser QUBE Servo 2 - USB](https://www.quanser.com/products/qube-servo-2/)
- [Quanser Aero 2](https://www.quanser.com/products/aero-2/)
- [Quanser AERO](https://www.quanser.com/products/quanser-aero/)
- [Quanser QArm](https://www.quanser.com/products/qarm/)
- [Quanser QArm Mini](https://www.quanser.com/products/qarm-mini/)


Before installing *Quanser SDK for Ubuntu x86_64* for the very first time on a target, execute the following commands: 

```
wget --no-cache https://repo.quanser.com/debian/release/config/configure_repo.sh
chmod u+x configure_repo.sh
./configure_repo.sh
rm -f ./configure_repo.sh
```



To install *Quanser SDK for Ubuntu x86_64*, or upgrade an existing installation, run the following commands:

```
sudo apt update
sudo apt-get install quanser-sdk
```


To uninstall and remove *Quanser SDK for Ubuntu x86_64*, run the following command:

```
sudo apt-get --auto-remove purge quanser-sdk
```
