74xx is a 7400 series integrated circuits library for [Logisim](http://www.cburch.com/logisim).

## Supported Chips

| Chip                | Description                         | Status                |
|:--------------------| ----------------------------------- | --------------------- |
| [7400](7400.md)     | quad 2-input NAND gate              | automated test passed |
| [7402](7402.md)     | quad 2-input NOR gate               | automated test passed |
| [7404](7404.md)     | hex inverter                        | automated test passed |
| [7408](7408.md)     | quad 2-input AND gate               | automated test passed |
| [7410](7410.md)     | tripe 3-input NAND gate             | automated test passed |
| [7411](7411.md)     | tripe 3-input AND gate              | automated test passed |
| [7420](7420.md)     | dual 4-input NAND gate              | automated test passed |
| [7421](7421.md)     | dual 4-input AND gate               | automated test passed |
| [7425](7425.md)     | dual 4-input NOR gate               | automated test passed |
| [7427](7427.md)     | tripe 3-input NOR gate              | automated test passed |
| [7432](7432.md)     | quad 2-input OR gate                | automated test passed |
| [7442](7442.md)*    | 4-line to 10-line decimal decoder   | untested |
| [7451](7451.md)*    | AND-OR-invert gates                 | untested |
| [7474](7474.md)     | dual D latch                        | untested |
| [7476](7476.md)     | dual JK flip flop                   | untested |
| [7485](7485.md)*    | 4-bit magnitude comparator          | planned |
| [7486](7486.md)     | quad 2-input XOR gate               | automated test passed |
| [74147](74147.md)   | 10-line to 4-line priority encoder  | automated test passed |
| [74157](74157.md)   | quad 2-line to 1-line data selector | untested |
| [74161](74161.md)   | synchronous 4-bit binary counter    | untested |
| [74163](74163.md)   | synchronous 4-bit binary counter    | untested |
| [74181](74181.md)*  | 4-bit arithmetic logic unit         | untested |
| [74244](74244.md)   | octal buffer                        | untested |
| [74247](74247.md)   | BCD to 7-segment decoder            | untested |
| [74283](74283.md)   | 4-bit binary full adder             | automated test passed |
| [74373](74373.md)*  | 8-bit transparent latch             | untested |
| [74377](74377.md)*  | 8-bit register with clock enable    | untested, not pure gate logic |
| [74574](74574.md)*  | 8-bit D-latch                       | planned |
| [74595](74595.md)*  | 8-bit shift register                | untested, not pure gate logic |
| [74670](74670.md)*  | 4 by 4 register file                | untested, not pure gate logic |
| [744075](744075.md) | triple 3-input OR gate              | automated test passed |
| [744078](744078.md)*| 8-input OR/NOR gate                 | untested |
| [744511](744511.md) | BCD to 7-segment decoder            | automated test passed |

(*) Documentation missing

* [Gates](gates.md)

## Design Rules

* Circuits are built from standard gates only
* Logisim pinout represents the DIP pin configuration of the corresponding chip

