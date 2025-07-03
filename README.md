# ⚡ CMOS Lab – Digital Logic Circuits with WinSpice

This repository contains SPICE netlists and simulation results created as part of my **CMOS Lab** coursework.  
The focus is on modeling and analyzing CMOS-based digital logic circuits using **WinSpice**, an NGSpice-compatible circuit simulator.

---

## 📌 About

In this lab, I explored:
- Writing SPICE netlists for CMOS digital gates (inverter, NAND, NOR, XOR, etc.)
- Simulating transient response and static behavior
- Understanding power consumption, propagation delay, and switching characteristics
- Learning practical aspects of digital VLSI design through simulation

All netlists were written manually in `.cir` or `.sp` files and tested in **WinSpice**.

---

## 🛠️ Tools Used

- **WinSpice** – Circuit simulation tool (compatible with NGSpice)
- Text editor or IDE (e.g., VS Code, Sublime, Notepad++) to edit netlists
- (Optional) Plot viewer included with WinSpice to view waveforms

---

Install WinSpice or NGSpice (see requirements.txt).

Open any .cir or .sp file in your text editor.

Run simulations in WinSpice:

Open WinSpice

Load the netlist:

bash
Copy
Edit
source inverter.cir
Run transient analysis or view waveforms.

📖 What’s Included
SPICE netlists for:

Basic CMOS gates (INV, NAND, NOR)

Combinational logic (MUX, XOR)

Sequential circuits (flip-flops)

Simulation setup and comments explaining each netlist

Sample output waveform files (.raw)
