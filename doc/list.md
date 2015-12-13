74xx is a 7400 series integrated circuits library for [Logisim](http://www.cburch.com/logisim).

## Supported Chips

| Chip             | Description                         | Status                |
|:-----------------| ----------------------------------- | --------------------- |
| [7400](7400)     | quad 2-input NAND gate              | automated test passed |
| [7402](7402)     | quad 2-input NOR gate               | automated test passed |
| [7404](7404)     | hex inverter                        | automated test passed |
| [7408](7408)     | quad 2-input AND gate               | automated test passed |
| [7410](7410)     | tripe 3-input NAND gate             | automated test passed |
| [7411](7411)     | tripe 3-input AND gate              | automated test passed |
| [7420](7420)     | dual 4-input NAND gate              | automated test passed |
| [7421](7421)     | dual 4-input AND gate               | automated test passed |
| [7425](7425)     | dual 4-input NOR gate               | automated test passed |
| [7427](7427)     | tripe 3-input NOR gate              | automated test passed |
| [7432](7432)     | quad 2-input OR gate                | automated test passed |
| [7442](7442)*    | 4-line to 10-line decimal decoder   | untested |
| [7451](7451)*    | AND-OR-invert gates                 | untested |
| [7474](7474)     | dual D latch                        | untested |
| [7476](7476)     | dual JK flip flop                   | untested |
| [7485](7485)*    | 4-bit magnitude comparator          | planned |
| [7486](7486)     | quad 2-input XOR gate               | automated test passed |
| [74147](74147)   | 10-line to 4-line priority encoder  | automated test passed |
| [74157](74157)   | quad 2-line to 1-line data selector | untested |
| [74161](74161)   | synchronous 4-bit binary counter    | untested |
| [74163](74163)   | synchronous 4-bit binary counter    | untested |
| [74181](74181)*  | 4-bit arithmetic logic unit         | untested |
| [74244](74244)   | octal buffer                        | untested |
| [74247](74247)   | BCD to 7-segment decoder            | untested |
| [74283](74283)   | 4-bit binary full adder             | automated test passed |
| [74373](74373)*  | 8-bit transparent latch             | untested |
| [74377](74377)*  | 8-bit register with clock enable    | untested, not pure gate logic |
| [74574](74574)*  | 8-bit D-latch                       | planned |
| [74595](74595)*  | 8-bit shift register                | untested, not pure gate logic |
| [74670](74670)*  | 4 by 4 register file                | untested, not pure gate logic |
| [744075](744075) | triple 3-input OR gate              | automated test passed |
| [744078](744078)*| 8-input OR/NOR gate                 | untested |
| [744511](744511) | BCD to 7-segment decoder            | automated test passed |

(*) Documentation missing

* [Gates](Gates)

## Design Rules

* Circuits are built from standard gates only
* Logisim pinout represents the DIP pin configuration of the corresponding chip

