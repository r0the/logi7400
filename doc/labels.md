# Pin Label Naming

Pin labels are named after a consistent schema that is a compromise between traditional naming, uniformity, and adherence to [VHDL](https://en.wikipedia.org/wiki/VHDL) syntax:

## Syntax

The label syntax is derived from the syntax of VHDL identifiers.

The following characters are used for pin labels:

'a' to 'z', 'A' to 'Z', '0' to '9', and '\_'

The first character of a label must be a letter, the last character may not be an underscore.
Upper- and lowercase letters are considered identical.

## Semantics

Label names identify the function of the corresponding pin.

| Labels            | Function                             |
|:----------------- |:------------------------------------ |
| VCC               | supply voltage                       |
| GND               | ground                               |
| A, B, C, D, J, K  | data input                           |
| Q, R              | data output                          |
| CLK               | rising or falling edge trigger input |
| SET               | set element to HIGH input            |
| CLR               | set element to LOW input             |
| OE                | output enable                        |
| CIN               | carry input                          |
| COUT              | carry output                         |

Corresponding inputs of multiple elements or multi-bit inputs and output are labelled with a letter followed by a digit:

A1, A2, Q1, Q2

Outputs intended for a seven segment display are labelled as follows:

Qa, Qb, Qc, Qd, Qe, Qf, Qg

