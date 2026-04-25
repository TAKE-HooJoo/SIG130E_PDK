# SIG130E PDK

SIG130E is an experimental open-source PDK for a virtual 130nm-class CMOS process.

This project aims to provide a lightweight and educational PDK environment that can be used on modest hardware, focusing on accessibility, transparency, and hands-on learning.

---

## ✨ Overview

- Technology node: 130nm (virtual process)
- Core voltage: 1.5V
- IO voltage: 3.0V
- Target: education / experimentation / hobby IC design

This PDK is designed to be:
- Easy to understand
- Easy to modify
- Fully open for exploration

---

## 🛠 Supported Tools

- KLayout (layout / DRC)
- xschem (schematic entry)
- ngspice (circuit simulation)
- Magic (layout / extraction)
- LVS (basic verification flow)

---

## 📂 Directory Structure

```text
SIG130E_PDK/
├── docs/        Process spec, layer definitions, design rules, devices
├── klayout/     Technology file, layer properties, DRC deck
├── xschem/      Symbols and device definitions
├── ngspice/     SPICE models (NMOS/PMOS)
├── magic/       Magic technology file
├── lvs/         LVS setup files
├── cells/       Primitive devices and standard cells
└── examples/    Sample circuits (inverter, ring oscillator, NAND2)
