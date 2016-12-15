# Logisim Library Design Guidelines

The following guidelines are derived from two goals:

- The library should be portable to [logisim-evolution](https://github.com/reds-heig/logisim-evolution)
  with minimum effort.

- The designeds circuits should be easily understandable and be usable in an educational context.

## Pin Layout

The pin layout must match the DIP pinout of the corresponding ICs.

## Usage of Built-in Components

Only certain built-in components are allowed:

### Wiring

Only *Pins* are allowed. Input pins are always on the west side of a circuit facing east, output
pins always on the east side facing west.

### Gates

The following gates are allowed: *NOT*, *AND*, *OR*, *NAND* *NOR*, *XOR*, *XNOR*, and
*Controlled Buffer*. Gates may not have inverted inputs. Instead, a separate inverter is used.
Bit size is always 1, gate size is always small.

## Memory

The library-defined circuits *D_Latch*, *D_Flip_Flop*, and *JK_Flip_Flop* must be used. Internally,
these circuits make use of the built-in *D Flip-Flop* and *J-K Flip_Flop*. The built-in flip-flops
may not be used anyplace else.

## Pin Label Naming

Pin labels are named after a consistent schema that is a compromise between traditional naming, uniformity, and adherence to [VHDL](https://en.wikipedia.org/wiki/VHDL) syntax:

## Syntax

The label syntax is derived from the syntax of VHDL identifiers.

The following characters are used for pin labels:

'a' to 'z', 'A' to 'Z', '0' to '9', and '\_'

The first character of a label must be a letter, the last character may not be an underscore.
Upper- and lowercase letters are considered identical.

## Semantics

Label names identify the function of the corresponding pin.

| Labels                     | Function                             |
|:-------------------------- |:------------------------------------ |
| VCC                        | supply voltage                       |
| GND                        | ground                               |
| A, B, C, D, E, F, G, J, K  | data input                           |
| Q, R                       | data output                          |
| CLK                        | rising or falling edge trigger input |
| SET                        | set element to HIGH input            |
| CLR                        | set element to LOW input             |
| OE                         | output enable                        |
| LE                         | load enable                          |
| CIN                        | carry input                          |
| COUT                       | carry output                         |

Corresponding inputs of multiple elements or multi-bit inputs and output are labelled with a letter followed by a digit:

A1, A2, Q1, Q2

Outputs intended for a seven segment display are labelled as follows:

Qa, Qb, Qc, Qd, Qe, Qf, Qg

