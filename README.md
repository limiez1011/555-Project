# blinky
Little led board that uses a 555 timer to clock a decade counter.

## Functionality
The NE555 is in AStable mode which creates a PWM signal that feeds into the CD4017, the PWM output is adjustable through the potentiometer, the CD4017 has 10 output pins which turn on sequentially every time it recieves a clock pulse, on our PCB this means that the leds will turn on after another in a circular pattern.

## BOM
- 1x NE555 Timer
- 1x CD4017 Decade counter
- 1x Potentiometer
- 2x Capacitors
- 2x Resistors
- 10x LED's
<img width="2144" height="1220" alt="image" src="https://github.com/user-attachments/assets/2e7f4de1-5ad6-4da9-b7ce-53ba9820d7cc" />
<img width="1347" height="998" alt="image" src="https://github.com/user-attachments/assets/42a80aee-dbaf-4f7a-bb68-184b5803acd1" />


