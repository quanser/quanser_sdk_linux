# Quanser SDK for Linux
This repository contains instructions for accessing the *Quanser SDK for Linux*, aimed at the 64-bit Linux operating system. 

The [Quanser SDK](https://github.com/quanser/quanser_sdk) facilitates application software development using Quanser hardware and virtual experiments. It provides device drivers and various Application Programming Interfaces (API's) in C and Python together with hardware interfacing, communication and vision libraries.



The *Quanser SDK for Linux* supports the following Linux targets: 
- Linux x86_64 (e.g., Ubuntu PC)
- [Quanser QBot Platform](https://www.quanser.com/products/qbot-platform/)
- [Quanser QDrone 2](https://www.quanser.com/products/qdrone-2/)





For the *Linux x86_64* target (e.g., Ubuntu PC), the *Quanser SDK for Linux* supports the following Quanser devices:

- [Quanser Qube-Servo 3](https://www.quanser.com/products/qube-servo-3/)
- [Quanser QUBE Servo 2 - USB](https://www.quanser.com/products/qube-servo-2/)
- [Quanser Aero 2](https://www.quanser.com/products/aero-2/)
- [Quanser AERO](https://www.quanser.com/products/quanser-aero/)
- [Quanser QArm](https://www.quanser.com/products/qarm/)





Before installing *Quanser SDK for Linux* for the very first time on a target, execute the following commands: 

```
wget --no-cache https://repo.quanser.com/debian/release/config/configure_repo.sh
chmod u+x configure_repo.sh
./configure_repo.sh
rm -f ./configure_repo.sh
```



To install *Quanser SDK for Linux*, or upgrade an existing installation, run the following commands:

```
sudo apt update
sudo apt-get install quanser-sdk
```





The *Quanser SDK for Linux* documentation is available through man pages.



For additional information about the *Quanser SDK*, including Quanser API's, examples and documentation, refer to:

https://github.com/quanser/quanser_sdk

