# Conversion Boards
Various boards to convert from one chip to another.  Unless stated otherwise, they are currently untested.

## [Mean Well GP25A13A-R1B Breakout](/MeanWell_GP25A13A-R1B_PSU)
A breakout board for the 5-pin DIN plug on this tri-voltage Mean Well PSU.<br>

## Logic Analyser Breakouts
Breakout boards to simplify connecting various ICs to a logic analyser via Dupoint-style wires:
- [MOS 6502](/6502_Logic_Analyser_Breakout)
- [MOS 6510](/6510_Logic_Analyser_Breakout)
- [Intel 8080](/8080_Logic_Analyser_Breakout)
- [CDP1802](/CDP1802_Logic_Analyser_Breakout)
- [Zilog Z80](/Z80_Logic_Analyser_Breakout)
- [Generic 40-pin](/Logic_Analyser_Breakout_40pin)

YouTube Videos:
- [Intel 8080](https://youtu.be/iMYuRV3rcPI)
- [Zilog Z80](https://youtu.be/R_pdPv_npmc)
- [MOS 6502](https://youtu.be/lU5GjI01oMk)

## D-sub Breakouts
Breakout boards for various D-sub type connectors:
- [DE9](/DE9_Breakout)
- [DA15](/DA15_Breakout)
- [DB25](/DB25_Breakout)

## EPROM Converters
Boards to convert between different ROM/PROM/EPROM types:
- [2716 to 2732](/2716-to-2732) ... switch between two 2KB ROM images
- [2764 to 27128](/2764-to-27128) ... switch between two 8KB ROM images
- [2764 to 68764](/2764-to-68764_Write) ... write a 68764 as a 2764
- [68764 to 2764 for reading](/68764-to-2764_Read) ... read a 68764 as a 2764
- [2764 to MK36000](/2764-to-MK36000) ... read an MK36000 as a 2764

## [DIN Breakout](/DIN_Breakout)
A breakout board for 5/6/7/8 pin DIN connectors.

## [SMQD Converter](/SMQD_Converter)
Idea is to use a surface mount crystal in place of the through-hole crystal.  Why?  Spectrum clones from the former Eastern Bloc tended to use 14MHz crystals which are not easy to come by anymore in through-hole form, but surface mount versions are.

### Status
20-Jun-2025: Test boards have been fabricated, not yet tested.<br>

## [Dual Soviet Western 40pin Socket](/Dual_Soviet_Western_40pin_Socket)
Soviet-era electronics used a 2.5mm pin pitch rather than 2.54mm/0.1" pin pitch we are accustomed to in the West.  This can cause problems with larger chips as they need to be bent slightly to fit.  Hence this idea to allow a Western chip to fit into a Soviet motherboard, like an Intel 8080A to replace a Soviet КР580ВМ80А.

### Status
20-Jun-2025: Test boards have been fabricated, not yet tested.<br>

![2.5mm pin pitch IC socket](/Dual_Soviet_Western_40pin_Socket/Dual_Soviet_Western_40pin_Socket_3D.png)

## [Soviet 40pin Socket](/Soviet_40pin_Socket)
The idea behind this design is to make a 2.5mm pin pitch IC socket for Soviet-era chips.

### Status
20-Jun-2025: Test boards have been fabricated, not yet tested.<br>

![2.5mm pin pitch IC socket](/Soviet_40pin_Socket/Soviet_40pin_Socket_3D.png)

## Soviet Keyswitch Replacement
Replacement designs for Soviet-era VM16 key switches.

### Status
26-Jul-2025: Initial PCB tested, requires adjustments

![Daughterboard & original](/Soviet-Keyswitch-Replacement/IMG_0261.jpeg)
