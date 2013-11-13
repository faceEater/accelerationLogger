A pre-release of my acceleration logger files for critique
	Not guaranteed to work!
	All licensed under CC-BY-SA 3.0

Summary:
    Dimensions: 1.25in x 2.5in * 1in
    Induction charged. Supercapacitor is charged by LT1618 from the coil(P2) and Bridge rectifier.
    Optical communications, serial@56kbaud
    Mating charging/comms circuit not yet designed
    Updatable firmware
    8Mbyte onboard flash
    Charges in <5 minutes with coil supplying 5v at a yet to be determined current (depends on charger)
    Powered from 5V, 5F supercap with LT1615-1 SEPIC Converter
    Linear postregulator for low noise
    Quiescent current < 200uA
    May or may not be potted, depending on requirements. Potted version is watertight.
    P1 for programming AVR + 2 GPIO & Serial
    Low power: <3mA at 1ksps for >30min battery life
    Fast sampling: 3 axis sampling at 1ksps/Axis
    3-axis
    200g full-scale, 100mg resolution 16-200g
    Sub 16-g resolution better than 5 mg
    4-layer board, believed to meet OSH park's design rules
    (Mostly) Arduino-compatible
    Atmega1284p processor
    Open Source -- CC-BY-SA 3.0

Github: https://github.com/faceEater/accelerationLogger
