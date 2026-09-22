# Li-Ion Charging and Protection Circuit

## Overview

This project presents a lithium-ion battery charging and protection circuit designed in **KiCad**. The circuit combines charging control, battery protection, status indication, and MOSFET-based isolation for safer battery operation.

## Key Components

### TP4056-42-ESOP8 Charging Controller
The **TP4056** provides constant-current/constant-voltage (CC/CV) charging for a lithium-ion cell using a 5 V input.

- Controls the battery charging process
- Uses the **RPROG resistor** to configure charging current
- Provides **CHRG** and **STDBY** outputs for charging-status indication

### DW01A Battery Protection IC
The **DW01A** monitors the battery and provides protection against unsafe operating conditions, including:

- Overcharge
- Over-discharge
- Overcurrent
- Short-circuit conditions

### N-Channel MOSFET Protection Stage
Two N-channel MOSFETs are controlled by the DW01A and act as electronic switches to disconnect the battery during abnormal operating conditions.

### Charging Status LEDs
Red and green LEDs are connected to the TP4056 status outputs to provide visual indication of the charging state.

### Micro-USB Input
A Micro-USB connector provides the 5 V input supply for the charging circuit.

## Design Features

- Lithium-ion CC/CV charging
- Overcharge protection
- Over-discharge protection
- Overcurrent protection
- Short-circuit protection
- MOSFET-based battery isolation
- Charging-status indication
- Micro-USB charging input

## Tools & Technologies

- KiCad
- Schematic Capture
- Power Electronics
- Lithium-Ion Battery Management
- Electronic Circuit Design

## Schematic

The complete circuit schematic is included in this repository.
