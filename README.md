# SIG130E PDK

SIG130E is an experimental open-source PDK for a virtual 130nm CMOS process.

## Process overview

- Technology node: 130nm class
- Core voltage: 1.5V
- IO voltage: 3.0V
- Target tools:
  - KLayout
  - xschem
  - ngspice
  - Magic
  - LVS flow

## Directory structure

```text
SIG130E_PDK/
├── docs/        Process documents, layer definitions, design rules
├── klayout/     KLayout technology, layer properties, DRC deck
├── xschem/      Symbols and device definitions
├── ngspice/     SPICE device models
├── magic/       Magic technology file
├── lvs/         LVS setup files
├── cells/       Primitive devices and standard cells
└── examples/    Example circuits
