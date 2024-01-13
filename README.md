# Disclaimer
This board is still a prototype and is not functional. I was not able to fabricate it with working mSATA or mPCIe. I attempted to fabricate it with JLCPCB using both JLC041611-7628 and JLC041611-3313 impedance control. The presence detect for mSATA was pulled low however the MinnowBoard would not communicate with the mSATA card. I've decided not to continue troubleshooting this board and instead leave it as a learning experience in high-speed board design.

See (CM4-NAS-MiniPCIE)[https://github.com/dumtux/CM4-NAS-MiniPCIE] as an example high-speed board designed for JLCPCB's JLC041611-7628 impedance control

# All-lure (GPIO, XDP, mPCIe, mSATA expansion for MinnowBoard)
All-lure is a custom "lure" expansion board for MinnowBoard Single Board Computers (SBC). The official hardware designs for MinnowBoard and the lures can be found at (MinnowBoards official GitHub)[https://github.com/MinnowBoard-org/design-files]. However, each board only exposes a single capability through the HSE (i.e. mSATA or mPCIe), instead I wanted a single board that combined as much of the lures capabilities into a single lure.

# Fabrication
This board does not work, please do not fabricate it. Currently it's designed for fabrication with JLCPCB using 1oz inner and outer copper weight and the standard JLC041611-7628 impedance control.


