# Harware to Software Integration
#### The following section documents the the hardware integration process used in this project. This includes the components used, the wiring configuration, as well as the transition to software configuration. 
### Components
* **Raspberry Pi** - The main controller that runs the Spotify software and read RFID tags. 

* **RFID RC522 (reader)** - Utilizes SPI interface, operates at 3.3V logic

* **RFID stickers (tags)** - Passive RFID tags containing a unique identifier (UID)

* **Bluetooth Speaker** - Plays a selected song when the RFID sticker is placed on top of the RFID reader.

* **Dupont Cables (Female to Female Jumper Wires)** - Used to wire the RFID reader to the Raspberry Pi. 

## The Hardware Setup
#### Solder the header pins into the RFID RC522. These pins will be used to connect the dupont cables from the RC522 to the Raspberry Pi. 

#### The cables are connected using the standard RC522 wiring configuration.

#### Incorporate USB powered speakers, these can either be plugged into the heaadphone jack of the Raspberry Pi, or in a separate outlet.

#### The RFID stickers placed underneath the bug model.

## Software Integration 
#### Install Raspberry Pi OS (The Bullseye version was used in this project)

#### Enable SPI in the Raspberry Pi OS software in order to use the RFID reader.

#### This project required several Python packages to be installed via Raspberry Pi OS command line. 

### Library:
    