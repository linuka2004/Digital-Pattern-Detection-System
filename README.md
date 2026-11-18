# Digital Pattern Detection System & PCB Design

A synchronous digital hardware system that generates binary patterns,
converts parallel data into a serial stream, and detects the binary
sequence `0011` using a Mealy finite state machine.

The project combines sequential logic design, clock synchronization,
circuit simulation, and custom PCB implementation.

## System Operation

### 1. Pattern Generation

A 4-bit Linear Feedback Shift Register (LFSR) generates
pseudo-random binary patterns.

### 2. Parallel-to-Serial Conversion

A 4-bit Parallel-In Serial-Out (PISO) shift register loads the
generated pattern and transmits its bits sequentially.

### 3. Pattern Detection

A Mealy finite state machine processes the serial input and
asserts its detection output when the sequence `0011` is received.

### 4. Clock Synchronization

All three subsystems share a common clock, with coordinated
loading, shifting, and state transitions.

## Design & Implementation

- FSM state diagrams, transition tables, and state encoding
- Boolean expression derivation and Karnaugh-map simplification
- Circuit implementation using 74HC-series digital logic ICs
- Proteus simulation and timing verification
- Three custom single-layer PCBs designed in KiCad
- Schematic capture, component placement, routing, and jumper connections
- Hardware integration, testing, and troubleshooting

## Technologies

- Digital Logic Design
- Linear Feedback Shift Registers
- PISO Shift Registers
- Mealy Finite State Machines
- 74HC-Series Logic ICs
- KiCad
- Proteus
- PCB Design

## Project Files

- `hardware/` — Circuit schematics and KiCad PCB design files
- `simulation/` — Proteus simulation files
- `images/` — Circuit photographs, PCB previews, and screenshots
- `docs/` — Project report, state diagrams, transition tables, and timing diagrams

## Author

**Linuka Jayasinghe**  
Computer Systems Engineering Undergraduate  
Sri Lanka Institute of Information Technology (SLIIT)  
