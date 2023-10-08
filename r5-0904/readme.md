# revision 5 - 2023 09 04
first implementation of buck convertor and BMI270. better tracking performance and better power efficiency. extension is omitted.
## specs
- BMI270 IMU
- TP4057 500mA
- battery charge switch MOSFET
- reset button
- 51021 RB type battery connector
- optional JST-PH battery connector
- no THT components 
- 3x4cm form-factor
- flat bottom surface
## firmware configuration
- Board: WeMos D1 Mini
- Primary IMU: BMI270
- IMU Rotation: 0
- battery detection 180k ohm (default)
## battery requirements
DTP103040 will work flawlessly
- 51021 connector or JST-PH 2 pin connector
- integrated over-discharge protection circuit
- 10x30x40mm size
