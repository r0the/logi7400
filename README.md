# Logi7400

[Logisim](http://www.cburch.com/logisim/) 7400 series integrated circuits library.

Currently includes the following chips:

[7400](doc/7400.md), [7402](doc/7402.md), [7404](doc/7404.md), [7408](doc/7408.md), [7410](doc/7410.md),
[7411](doc/7411.md), [7414](doc/7414.md), [7420](doc/7420.md), [7421](doc/7421.md), [7425](doc/7425.md),
[7427](doc/7427.md), [7430](doc/7430.md), [7432](doc/7432.md), [7442](doc/7442.md), [7451](doc/7451.md),
[7474](doc/7474.md), [7476](doc/7476.md), [7486](doc/7486.md), [74109](doc/74109.md),
[74147](doc/74147.md), [74157](doc/74157.md), [74161](doc/74161.md), [74163](doc/74163.md),
[74181](doc/74181.md), [74244](doc/74244.md), [74247](doc/74247.md), [74283](doc/74283.md),
[74373](doc/74373.md), [74374](doc/74374.md), [74377](doc/74377.md), [74595](doc/74595.md),
[74670](doc/74670.md), [744049](doc/744049.md), [744075](doc/744075.md), [744078](doc/744078.md),
[744511](doc/744511.md)

You're welcome to request missing chips by opening an issue.

## Goal

This library aims to be a comprehensive 7400 series library for Logisim for designing logical circuits and for educational purposes.

The library should be compatible both with original [Logisim](http://www.cburch.com/logisim/) and [logisim-evolution](https://github.com/reds-heig/logisim-evolution).

## Design Guidelines

To meet these goals, the following design guidelines are met:

* Circuits are build from a minimal set of built-in components.
* The pin layout matches the DIP pinout of the corresponding chips.
* Automated tests are provided.
* Labels must conform to [VHDL](https://en.wikipedia.org/wiki/VHDL), i.e. start with a letter and contain only letters, digits, or underscores.

## Progress

See [documentation](doc/README.md) for details. Currently, circuits from other libraries are 
being integrated will later be redesigned to meet the guidelines.

## Credit

* [logisim_74v1](http://74x.weebly.com/blog/library-of-7400-logic-for-logisim), Public Domain
* [7400 series Logisim library from Ben Oztalay](http://www.cburch.com/logisim/download/7400-lib.zip]): Provided on Logisim web site, Public Domain
