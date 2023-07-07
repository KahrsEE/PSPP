# PSPP
Power Supply Prototype Platform

Based on the platform used by ridley engineering in power supply workshops.

The platform consists of: 
-	two input power connectors: a connection for the main DC bus, and a connection for auxiliary power to power the controller module.
-	A multi-diameter capacitor footprint for standard through-hole capacitor sizes. The different diameters are to accommodate different input and output voltage levels.
-	A controller module. The controller takes the auxiliary power, an optional current sense signal or voltage signal, and an error amplifier signal as an input. The controller module outputs up to six gate drive signals (four for a full bridge converter, two for synchronous rectification).
-	A switch module. The switch module takes in the main bus as an input. The switch module can consist of MOSFETs, IGBTs, or GaN FETs.
-	A rectifier module. The rectifier module takes the secondary voltage of the transformer (or inductor) as an input and uses either diode rectifiers or synchronous rectifiers to rectify the output.
Each module is connected through a 20 pin through-hole connector (pitch 0.100”, 2 rows, 10 pos). See SFH11-PBPC-D10-ST-BK.
