# AnetMarlinHermeraAzteegX5mini
Files used in 3D printer config

Anet A8 Printer
Hotend/Extruder replaced with E3D Hermera (12v direct)
Anet v1.5 Board removed
Azteeg X5 Mini added with VIKI2 LCD
TMC2224 Stepper Drivers
Marlin 2.0 (bug fix Jul 2020) replaced smoothie ware
Induction Probe replaces Z-End stop switch (BN-10-30V Clone)

- AZTEEG PIN WIRE/MODS
BN-10-30V Prox sensor probe - Remove brown (+V) wire from harness. Re-wire to 12V+ (no 12v on pin 1.28 nor 1.29). Blue and black wire on pin 1.28
Re-arrange wires for X,Y end stop harness to match pins on Azteeg (Trim edges of plastic harness for better fitment on board, GND & SIG). Anet stock harness will short board
Make adapter to allow Z1 and Z2 stepper motors connect in parallel




