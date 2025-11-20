# Сириус (Sirius) Sinclair ZX Spectrum Clone
## Introduction
I have two examples of this machine - they have the same case & keyboard but the motherboard is different.  I'm mainly interested in the smaller board as this seems to be the smallest implementation of a ZX Spectrum I've come across.

This machine was initially a bit of a mystery - well, obviously it's a Sinclair ZX Spectrum clone.  It has all Soviet-era parts (dated mostly 1991 & 1992) including a beautiful, ceramic Т34ВМ1 CPU, a Т34РЕ1-020 ROM (containing the Czechoslovak "Didaktik Skalica" firmware) and absolutely no manufacture markings on the case or motherboard.

Thanks to some sleuthing by Martin (via Patreon) who discovered that the machine (case at least) appears to be a "Sirius" from Russia (confirmed also with UCHC, Ukrainian Computing History Community, on Telegram):
https://sblive.narod.ru/ZX-Spectrum/Sirius/Sirius.htm

Thanks to Eugene on UCHC for his insight:
"Actually, this is one of numerous cheap clones that built around latest Soviet ULA replacement. This one, in particular, created by small garage company with a quite shitty soldering and assembling.  And board itself seems to be assembled somewhere using automated production line, so seems they have ordered boards somewhere else and then assemble them in case. This can explain why boards in these instances are different."

It was initially AC powered with a very simple and unsafe looking transformer (assuming 220VAC-to-9VAC), a КЦ410Б bridge rectifier and a КРЕН5А 5V linear regulator.  I will replace these with a simple 2.1mm DC socket for direct 5VDC input (i.e. USB charger).  On booting it was drawing about 330mA at 5V.

It utilises a Soviet equivalent to a Gate Array or ULA called a БМК (Базового Матричного Кристалла, or Basic Matrix Crystal) ... the КА1515ХМ1-216.  I have had very little success with machines that use this chip actually working ... however it does greatly simplify the circuit design!

The only other major chips are the Т34ВМ1 Soviet Z80 clone, later called the КР1858ВМ1 or КМ1858ВМ1 depending on case type), a Т34РЕ1 (Spectrum ROM), 64KBytes of DRAM using КР565РУ5 and a few other support chips.

The machine only has three ports: 5-pin DIN for joystick, 5-pin DIN for RGBS video & sound output and a 3-pin DIN for cassette input/output.  It also has a reset button.

## Videos
- [Сириус (Sirius) ZX Spectrum Clone: Part 1 (First Look & Power On)](https://youtu.be/TphnZRfjiL4)
- [Сириус (Sirius) ZX Spectrum Clone: Part 2 (RGB & Tape In)](https://youtu.be/R5iWXHqjOgQ)
- [Сириус (Sirius) ZX Spectrum Clone: Part 3 (Smallest Speccy board?)](https://youtu.be/3xgzQrBvwQw)

## [Original Information](/Original_Documentation)
Original schematic & board layout details from [here](https://sblive.narod.ru/ZX-Spectrum/Sirius/Sirius.htm).

## [Updated Schematic](/New_Schematic)
I'm working on creating a cleaner version of the schematic.  I originally wanted to use it as a basis for a new design using the БМК but there is already a modern design available [[LUT216]](https://sblive.narod.ru/ZX-Spectrum/LUT216/LUT216.htm) that looks quite interesting.

### Status
15-Jun-2025: Updated KiCad schematic is work-in-progress<br>

## [Interface Board](/Interface_Board)
Such a beautiful little board deserves to be seen and not hidden away in some ho-hum case.  I'm planning to mount my Sirius board on a Perspex place with a membrane keyboard.  Thus I need a separate board with all the interfaces on it, hence this design.

### Status
16-Jun-2025: Submitted to PCBWAY for test fabrication<br>


## [Images](/Images)
Pictures of my machine.
