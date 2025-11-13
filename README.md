# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

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
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS

<img width="850" height="569" alt="image" src="https://github.com/user-attachments/assets/d9597b5c-5c6a-4668-b232-ad10f0271c96" />




### 2. Schematic of Full Custom 2:1 MUX

<img width="1584" height="824" alt="image" src="https://github.com/user-attachments/assets/6bfcf415-9ab4-425b-a13f-521bcf6dec90" />



### 3. Transient Response Setup

<img width="1579" height="844" alt="image" src="https://github.com/user-attachments/assets/63905727-ffa7-454e-bc4b-1d4371c11857" />


<img width="1411" height="745" alt="image" src="https://github.com/user-attachments/assets/4b925b7c-0da1-48a3-a408-0db71fcb5433" />


## Output

### 1. Transient Analysis Output

<img width="1411" height="719" alt="image" src="https://github.com/user-attachments/assets/e9d0753e-ae41-49f9-ac5b-cb8e6bef5c02" />


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
