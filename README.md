# Logisim74xx

[Logisim](http://www.cburch.com/logisim/) 7400 series integrated circuits library

## Goal

This library aims to be a comprehensive 7400 series library for Logisim for designing logical circuits and for educational purposes.

The library should be compatible both with original [Logisim](http://www.cburch.com/logisim/) and [logisim-evolution](https://github.com/reds-heig/logisim-evolution).

## Design Guidelines

To meet these goals, the following design guidelines are met:

* Circuits are build from standard gates only (AND, OR, XOR, NAND, NOR, XNOR, inverter, and tri-state buffer).
* The pin layout matches the DIP pinout of the corresponding chips.
* Automated tests are provided.
* Labels start with letter.

## Progress

See [Wiki](https://github.com/r0the/74xx/wiki) for a list of supported chips. Currently, circuits from other libraries are 
being integrated will later be redesigned to meet the guidelines.

## Credit

* [logisim_74v1](http://74x.weebly.com/blog/library-of-7400-logic-for-logisim), Public Domain
* [7400 series Logisim library from Ben Oztalay](http://www.cburch.com/logisim/download/7400-lib.zip]): Provided on Logisim web site, Public Domain
