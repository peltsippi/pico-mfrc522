Pico C/C++ SDK library for MFRC522.

Tested with this RC522 module: https://www.az-delivery.de/en/products/rfid-set. 

Based on the arduino library for MFRC522 https://github.com/miguelbalboa/rfid. Modified the library by https://github.com/luisfg30/rfid so that it works for the Pico. See those projects for more information. 

Datasheet: https://www.nxp.com/docs/en/data-sheet/MFRC522.pdf

Notes from Timo P:
Idea is to refactor all init functions etc away from the code.
Possibly also convert to c++ (using https://github.com/Harbys/pico-ssd1306.git as reference)

Work in progress!

Update:
it seems that all my reader modules are counterfeit and non-functional.
I'll probably just abandon this and pick some other chip instead.