# RFID with a Raspberry Pi Pico

This library enables the MFRC522 module to connect to the Raspberry Pi Pico.

Code mostly from: <https://github.com/danjperron/micropython-mfrc522>


## Wiring
The Raspberry Pi Pico connects to the RC522 module via the SPI interface. The default pinouts are provided below: 

| RFID Signal | Pico Pin |
|-------------|:--------:|
| SCK         |   GP2    |
| MOSI        |   GP3    |
| MISO        |   GP4    |
| RST         |   GP0    |
| SDA         |   GP1    |

---

## Programs and Libraries
There are three programs and 2 libraries:

- `ndef_create.py` - creates NDEF tags
- `ndef_erase.py` - erases NDEF tags
- `ndef_read.py` - reads NDEF tags

---

- `rfidaccess.py` - used for accessing the rfid chip memory 
- `mfrc522.py` - the main RC522 module library 

---

## STL files for 3d printing the case
There are two files: [`Top.stl`](Top.stl) and [`Bottom.stl`](bottom.stl) that you can print out to encase the RC522 module.