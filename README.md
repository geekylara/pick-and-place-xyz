# Pick and Place XYZ

Automation project developed using **Siemens TIA Portal V15.1**, **PLCSIM** and **Factory I/O** for the simulation and control of an industrial **Pick & Place XYZ** station.

---

## Project Overview

This project implements the control logic of an automated Pick & Place XYZ station using a Siemens PLC.

The system detects a workpiece, executes a predefined movement sequence through the X, Y and Z axes, picks the part, transfers it to the target position and releases it before returning to its initial state, ready for the next cycle.

The entire process was validated using **Factory I/O** and **PLCSIM**, allowing the PLC program to interact with a virtual industrial environment without requiring physical hardware.

---

## Objectives

- Develop the PLC logic for an automated Pick & Place system.
- Simulate the complete industrial process using Factory I/O.
- Validate the sequence of operation through Siemens PLCSIM.
- Apply industrial automation concepts in a virtual environment.

---

## Project Features

- Automatic operation sequence
- XYZ axis positioning
- Pick and release mechanism
- Industrial sensors
- Sequential PLC control
- Factory I/O simulation
- Virtual commissioning using Siemens PLCSIM

---

## Software Requirements

| Software | Version |
|----------|----------|
| Siemens TIA Portal | V15.1 |
| Siemens PLCSIM | V15.1 |
| Factory I/O | Compatible with TIA Portal V15.1 |

---

## System Operation

The general operating sequence is:

1. System initialization.
2. Detection of a workpiece.
3. Positioning of the X axis.
4. Positioning of the Y axis.
5. Lowering of the Z axis.
6. Picking the workpiece.
7. Raising the Z axis.
8. Transport to the destination.
9. Lowering the Z axis.
10. Releasing the workpiece.
11. Returning to the home position.
12. Waiting for the next cycle.

---

## Technologies Used

- Siemens TIA Portal
- Siemens PLCSIM
- Factory I/O

---

## How to Open the Project

### TIA Portal

1. Open Siemens TIA Portal V15.1.
2. Select **Open project**.
3. Navigate to:

```
TIA-Portal/Pick & Place XYZ/
```

4. Open:

```
Pick & Place XYZ.ap15_1
```

---

### Factory I/O

1. Open Factory I/O.
2. Load the included Factory I/O scene.
3. Connect Factory I/O with Siemens PLCSIM.
4. Start the PLC simulation.
5. Run the simulation.

---

## Notes

This repository was created for educational purposes as part of an Industrial Automation project.

The project demonstrates the implementation of sequential PLC control logic in a virtual industrial environment using Siemens automation software.

---

## Author

**David Ernesto Lara Barbosa**

Electronic Engineering Student


## License

This project is distributed under the MIT License.