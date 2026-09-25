# 12v-rgb-led-strip-common-anode-driver
12v rgb led strip common anode driver using only a ne555p

Vcc is 12V
pin 3 of IRFZ44N goes to the respective color you want to modulate 
Duty Cycle: `99.8%`

## Schematic
![schematic](/image.png)

### Breadboard wiring

![breadboard](/20260925_203341.jpg)

### BOM

| Reference | Value | Qty |
|---|---|---|
| C1 | 10nF | 1 |
| C2 | 100nF | 1 |
| D1, D2 | 1N4148 | 2 |
| Q2 | IRFZ44N | 1 |
| R1 | 1k | 1 |
| R2, RV1 | 10k | 2 |
| U1 | NE555P | 1 |

#### i used 103 & 104 AEC as c1 & c2 respectively
