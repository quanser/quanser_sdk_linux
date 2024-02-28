# The Quanser SDK for Linux
The Quanser SDK for the 64-bit Linux operating system provides device drivers and a set of C and Python API's for aiding in application software development using Quanser hardware. 

The Quanser SDK for Linux supports the following targets: 
- Linux x86_64 (e.g., Ubuntu PC)
- Quanser QBot Platform
- Quanser QDrone 2 

For the Linux x86_64 target, the Quanser SDK for Linux supports the following Quanser devices:
- Quanser Qube-Servo 3
- Quanser QUBE Servo 2 - USB 
- Quanser Aero 2
- Quanser AERO
- Quanser QArm

To install the Quanser SDK for Linux for the first time, run the following commands: 
- wget --no-cache https://repo.quanser.com/debian/release/config/configure_repo.sh
- chmod u+x configure_repo.sh
- ./configure_repo.sh
- rm -f ./configure_repo.sh
- sudo apt update
- sudo apt-get install quanser-sdk

To upgrade an existing Quanser SDK for Linux installation, run the following commands: 
- sudo apt update
- sudo apt-get upgrade quanser-sdk
