# Arduino ISP

Ready to start example. Just open it with Visual Studio Code and enjoy!

1. Connect USB-UART 5V, GND, RX, TX, DTR to Arduino Pro Mini.
2. Choose ProMini->Upload to burn Arduino ISP firmware.
3. Disconnect DTR.
4. Connect Pro Mini pins to Uno ISCP connector:
    Arduino Pro Mini (ISP) | Uno (Target)
    --- | ---
    5V  |  5V
    GND |  GND
    10  | RST
    11  |MOSI
    12  |MISO
    13  | SCK
5. Choose Uno->Upload to burn Arduino ISP firmware to Uno.
   It's just working example, you can upload any firmware
   or bootloader this way.
