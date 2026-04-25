````markdown
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
````

---

## 🚀 Getting Started

### 1. Clone repository

```bash
git clone https://github.com/TAKE-HooJoo/SIG130E_PDK.git
cd SIG130E_PDK
```

### 2. Open with KLayout

* Load `klayout/tech/sig130e.lyt`
* Apply layer properties `klayout/lyp/sig130e.lyp`

### 3. Run simulation

```bash
ngspice ngspice/models/sig130e_models.spice
```

---

## 📘 Documentation

* `docs/process_spec.md` — Process overview
* `docs/layer_definition.md` — Layer mapping
* `docs/design_rules.md` — DRC rules
* `docs/device_spec.md` — Device parameters

---

## 🔬 Examples

* Inverter
* Ring Oscillator
* NAND2

Located under:

```
examples/
```

---

## ⚠️ Status

🚧 Under active development

* Initial PDK structure defined
* Basic device models under construction
* DRC/LVS flow in progress

---

## 🎯 Roadmap

* [ ] Complete layer definition
* [ ] Implement full DRC deck
* [ ] Add LVS flow
* [ ] Develop standard cell library
* [ ] Characterization (Liberty generation)
* [ ] OpenLane / flow integration

---

## 🤝 Contributing

Contributions are welcome!

* Issues
* Pull requests
* Ideas / experiments

---

## 📜 License

TBD (planned: open hardware / open PDK friendly license)

---

## 💡 Concept

> “From a PDK you build, to a PDK people actually use.”

This project is part of an effort to explore open-source IC design workflows in a practical and accessible way.

---

## ✍️ Author

TAKE-HooJoo (@SIG)

```

---


