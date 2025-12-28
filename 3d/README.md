# 3D Visualization Engine

DIANA is capable of processing complex 3D geometries in **CPACS** format by leveraging the **TIGL** software library. 

### Technical Workflow
1. **Backend Integration**: DIANA invokes TIGL to parse the aircraft design data and generate a high-fidelity **STL file**.
2. **Frontend Rendering**: The resulting geometry is loaded and rendered in the browser using the **Three.js** library, ensuring a smooth and interactive user experience.

### Key Interactive Features
* **Dynamic Visualization**: Full control over camera angles, zoom, and object orientation.
* **Automated Dimensioning**: An intelligent system that automatically calculates and displays aircraft measurements.
* **Customization Settings**:
    * **Toggle Measures**: Decide which specific dimensions to show or hide via a dedicated settings menu.
    * **Opacity Control**: Includes a real-time slider to adjust the transparency of the 3D model for internal inspection.

<img width="1911" height="915" alt="3D Visualization Demo" src="https://github.com/user-attachments/assets/bbebbb60-ebc2-4847-8ef3-30968f795187" />



