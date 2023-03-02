# CNC Foam Cutter

## Offer View
This repository contains the firmware and software necessary for operating an Arduino Mega 2560 board with the GRBL-HotWire-Mega-5X-Application-V5.12.
This repository also contains the .stl files and the hardware list to build this CNC machine. 

## Table of Contents
#### [Hardwere](https://github.com/wernerkleinhans/CNC-Foam-Cutter#hardwere-1)
#### [3D Parts and required hardware](https://github.com/wernerkleinhans/CNC-Foam-Cutter#3d-parts-and-required-hardware-for-one-side)
#### [Total Hardwere](https://github.com/wernerkleinhans/CNC-Foam-Cutter#total-hardwere-for-both-sides)
#### [Rails and Rods](https://github.com/wernerkleinhans/CNC-Foam-Cutter#total-rails-and-rods-for-both-sides)
#### [Electronics](https://github.com/wernerkleinhans/CNC-Foam-Cutter#all-electronics)
#### [Firmware and Software](https://github.com/wernerkleinhans/CNC-Foam-Cutter#firmware-and-software-1)
##

## Hardwere

### 3D Parts and required hardware (for one side)

| 3D Parts | Type               | Length | Amount | Nyloc Nuts |
|----------|--------------------|--------|--------|------------|
| Rod End 1| M4 countersunk bolt| 75mm   | 4      | 4          |
| Rod End 2| M4 countersunk bolt| 75mm   | 4      | 4          |
| X motor  | M3 allen cap bolt  | 40mm   | 4      | 4          |
|          | M3 allen cap bolt  | 10mm   | 4      |            |
| Y top    | M4 allen cap bolt  | 30mm   | 2      | 2          |
| X slid botom | M6 allen cap bolt | 50mm | 6      | 6          |
| X slid   | M4 allen cap bolt  | 25mm   | 4      | 4          |
| Y slid   | M4 allen cap bolt  | 25mm   | 1      | 1          |
|          | M4 allen cap bolt  | 20mm   | 2      | 2          |
| Y motor mount | M3 allen cap bolt | 10mm| 4      |            |
|          | M4 allen cap bolt  | 20mm   | 4      | 4          |

### Total Hardwere (for both sides)
#### Bolts

| Type                | Length | Amount |
|---------------------|--------|--------|
| M6 allen cap bolt   | 50mm   | 12     |
| M4 countersunk bolt | 75mm   | 16     |
| M4 allen cap bolt   | 30mm   | 4      |
| M4 allen cap bolt   | 25mm   | 10     |
| M4 allen cap bolt   | 20mm   | 12     |
| M3 allen cap bolt   | 10mm   | 16     |
| M3 allen cap bolt   | 40mm   | 8      |

#### Nuts

| Type          | Amount |
|---------------|--------|
| M6 nyloc nuts | 12     |
| M4 nyloc nuts | 42     |
| M3 nyloc nuts | 16     |

### Total Rails and Rods (for both sides)

| Type | Specifications | Amount |              
| --- | --- | --- |
| M10 threaded rod | 1000mm | 2 |
| M10 threaded rod | 500mm | 2 |
| 12mm en8 rod | 1000mm | 4 |
| 12mm en8 rod | 500mm | 4 |
| Bearing | 6000 ZZC | 4 |
| Flex Coupler | 5mm to 10mm | 4 |
| Driver Nuts | M10 nuts | 8 |

### All Electronics

| Type | Specifications            | Amount |
|------|---------------------------|--------|
| MotherBoard    | Arduino Mega 2560         | 1      |
| CNC Shield     | RAMPS 1.4 ARDUINO SHIELD  | 1      |
| STEPPER MOTOR  | nema 17                   | 4      |
| STEPPER MOTOR DRIVERS | A4988 DRIVER     | 4      |
| Limit Switches | Any                       | 4      |
| Power Supply   | 12-35V DC                 | 1      |
| Nichrome Wire  | 28 gauge                  | 1      |
##


## Firmware and Software

### To install the firmware for the Mega 2560 board, follow these steps:

##### Download and extract the zip file from this repository to your local drive.

1. Open the Arduino IDE.
2. Press "Ctrl+O" to open a sketch file.
3. Navigate to the /grbl-Mega-5X-firmware-1.02/grbl/examples/grblUpload/ folder in the extracted zip file.
4. Open the grblUpload.ino file.
5. Connect your Mega 2560 board to your computer using a USB cable.
6. Select "Arduino Mega 2560" from the "Tools > Board" menu.
7. Select the appropriate serial port from the "Tools > Port" menu.
8. Upload the firmware by clicking the "Upload" button or pressing "Ctrl+U".

### To install the HotWire Application on Windows, follow these steps:

1. Install "Win 10 32bit" on a virtual machine.
2. Change the Windows display settings as necessary.
3. Navigate to the /GRBL-HotWire-Mega-5X-Application-V5.12 folder/ in the extracted zip file.
4. Double-click on the setup.exe file to install the application.

#### Usage
Once the firmware and software are installed, you can use the HotWire Application to control the Mega 2560 board, to operate the hot wire foam cutter and send g-code. 

#### Credits
This repository is based on the GRBL firmware and the HotWire Application developed by the community. Special thanks to the developers and contributors who made this possible.
