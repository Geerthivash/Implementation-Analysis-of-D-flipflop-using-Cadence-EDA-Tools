# Ex No: 03 - Implementation & Analysis of D Flip-Flop using Cadence EDA Tools
## GEERTHIVASH J D
## 212223060067

## Aim
The aim is to design, implement, and analyze a D flip-flop using Cadence EDA tools, ensuring accurate sequential logic operation through waveform analysis and performance verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the D flip-flop design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Design the D flip-flop circuit with key components such as clock signal input, D input, and Q output.
- Implement feedback connections to enable sequential behavior.
- Connect appropriate voltage sources for logic control and supply.

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe timing behavior and output transitions.
- Set simulation parameters such as clock frequency, voltage levels, and delay conditions.
- Use Spectre simulator to perform transient analysis and functional verification.

### 4. Waveform Analysis
- Observe the output waveform to confirm correct D flip-flop functionality.
- Ensure that the Q output follows the D input on the rising edge of the clock signal.

## Circuit Diagram

### 1. Schematic of D Flip-Flop
![Screenshot 2025-03-25 094932](https://github.com/user-attachments/assets/2e33e857-4aed-45ea-9ee7-6a0fe346169b)


### 2. Transient Response Setup
*
![IMG-20241019-WA0010](https://github.com/user-attachments/assets/e532f49e-b60f-4629-bb39-9f9b4085b36f)*


 ![IMG-20241019-WA0013](https://github.com/user-attachments/assets/92433262-d11d-460f-899b-5c3d1e661266)

## Output

### 1. Transient Analysis Output
### Positive Latch
![Screenshot 2025-03-25 094917](https://github.com/user-attachments/assets/fa94cc50-5933-40bf-846f-db6294ce6d9f)
### Negative Latch
![Screenshot 2025-04-12 101445](https://github.com/user-attachments/assets/83b688cb-3477-42b3-8279-cc6009a991a0)


## Results
1. Successfully designed the D flip-flop schematic using Cadence EDA tools.
2. The simulation results verified the correct sequential logic behavior, ensuring that the Q output correctly follows the D input on the rising edge of the clock.
3. The waveform analysis demonstrated the expected timing behavior and performance of the D flip-flop circuit.
