# Evil-Twin-Project

## introduction

An Evil Twin is a fraudulent Wi-Fi access point that appears to be legitimate but is set up to eavesdrop on wireless communications.               
This type of attack may be used to steal the passwords of unsuspecting users, either by monitoring their connections or by phishing.

## Tool details

1. Scan a WLAN in the environment for a minute and view the various networks discovered.
2. Selection of the network on which to carry out the attack.
3. Presenting clients of the network on which the attack is being made.
4. Selecting a victim and performing an Evil-Twin attack.

Evil-Twin attack includes:<br>
Disconnecting the victim from the existing network, uploading the malicious network (the evil twin) and activating CaptivePortal, connecting the victim to the malicious network and its activities, obtaining the information that is the purpose of the attack.

In addition, there is a defense tool that detects the existence of an attack on the victim and prevents the success of the attack.

## Requirements
1. Two network interfaces, which both support monitor mode.
2. Linux operating system.
3. Python 3.0 or above.
4. Copy html file from project to path in your OS: /var/www

## How to run the project
1. Clone the repository
  ```sh
  git clone https://github.com/LiorAtiya/Evil-Twin-Project.git
  ```
2. Install Scapy
  ```sh
  sudo apt install python3-scapy    
  ```
3. Run the following command
  ```sh
  sudo python3 main.py
  ```
4. Set your interfaces (network adapters).
5. Select 1 to activate the Evil-Twin attack or select 2 to activate the defense mode.
6. Keep following the instructions on your terminal.

## Running example

  <h4 align="center">Menu Start:<h4>
  <p align="center">
    <img width="500" height="400" src="https://i.postimg.cc/9FFCB8ND/menu.jpg" />
  </p>
  <h4 align="center">Scanning AP:<h4>
    <p align="center">
  <img width="500" height="400" src="https://i.postimg.cc/bw4ZWcKC/scanAP.jpg" />
  <h4 align="center">Scanning Clients:<h4>
    <p align="center">
  <img width="400" height="250" src="https://i.postimg.cc/Cxn1jrzj/scan-Client.jpg" />
  <h4 align="center">CaptivePortal (Fake AP):<h4>
    <p align="center">
  <img width="250" height="400" src="https://i.postimg.cc/SRP8D2qR/captive-Portal.jpg" />
