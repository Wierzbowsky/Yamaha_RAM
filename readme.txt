Yamaha YIS503 RAM Board
-----------------------
Designed by Kamil Karimov (k2k@list.ru)
Homepage: http://caro.su/

This reposity contains PCB and Gerber files as well as pictures and the schematics for the Yamaha YIS503 RAM
board designed by Kamil Karimov. The board can be used as 512kb and as 1mb RAM expansion in Yamaha MSX2 computers
without any modification to the mainboard. To be used in Yamaha MSX1 computers a few additional components must be
installed onto the mainboard to support missing signals.

Mr. Karimov gave his permission to put his files into the repository. However it's not allowed to use any of the
files in this repository for commercial purposes without the permission from the author. Making a small batch of
boards, using some of the boards for personal projects and selling the remaining boards is permitted.

The following chips can be installed onto the board:

- SAMSUNG  K6X4008C1F-BF55
- HM628512LFP-7
- ALLIANCE AS6C4008-55SIN

These are SOP32 512kb chips. The timings are not impprtant. Anything from 50ns to 150ns works.

By default the board needs 2 chips to be installed that will create 1mb of RAM expansion. However it's possible to install only one chip. To do this the bridge marked as R2 needs to be cut and a 2kOhm resistor needs to be soldered at R1. The single chip must be installed at DD3.
