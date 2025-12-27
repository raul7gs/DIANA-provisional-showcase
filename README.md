### DIANA: Provisional Portfolio
**Note:** This repository is a provisional portfolio. The full application is scheduled to be open-source soon. Currently, the source code is proprietary to **DLR**; however, a **live technical demo** is available upon request.

<img width="1091" height="373" alt="image" src="https://github.com/user-attachments/assets/f3aff648-4d6e-431c-8594-3391a02a954f" />

### Overview
**DIANA (Data Interactive Analysis and Navigation Application)** is a web-based platform that enables users to transform complex data into meaningful, interactive visualizations. Through an **intuitive graphical interface**, users can explore datasets, generate customized visuals, and organize them into **dynamic dashboards** for a comprehensive overview of their data landscape. DIANA empowers analysts and decision-makers to uncover actionable insights faster.

### Data Integration
* **XML Input:** DIANA accepts XML files conforming to the **CPACS data standard**. This enables the automatic generation of plots through predefined "design kits" that target specific parts of the aircraft data model.
* **CSV Support:** Users can leverage DIANA’s general plot creation functionality for datasets that do not follow the CPACS schema, providing full flexibility for manual variable selection.
* **High Performance:** Optimized to handle **large-scale datasets** (moving from MB to GB-scale) with high responsiveness.

### Publication
For more technical details, please refer to the official paper:
* Sánchez, R. G., Mancini, A., Nugnes, V., Fröhler, B., & Gerlinger, B. **"DIANA: Data Interactive Analysis and Navigation Application"**. *AIAA AVIATION FORUM AND ASCEND 2025* (p. 3449).
 **[Read the paper here](https://www.researchgate.net/publication/393770335_DIANA_Data_Interactive_Analysis_and_Navigation_Application)**
---

### 📂 Portfolio Structure

* **[📁 DIANA Architecture & Components](./components-guide)** A visual breakdown of the app's logical structure. Includes descriptions and screenshots of the core modules: **Data Reading, Charts generation, Dashboard generation & Automatic report**.

* **[📁 DIANA Practical Example](./example-case)** A step-by-step walkthrough of a real use case. See how **CPACS/XML data** is transformed into actionable engineering insights through specific design kits.

* **[📁 3D Visualization Engine](./3d-engine)** A dedicated look at the **Three.js** implementation. Includes images of the **interactive 3D aircraft models** and the automated dimensioning system.

### Example of incoming website

The incoming public website, as observed, will include the the app itself,  documentation, releases, more example cases and other technical details. 

<img width="1915" height="908" alt="full" src="https://github.com/user-attachments/assets/35a68036-b844-489a-93d4-53edf63f728e" />

