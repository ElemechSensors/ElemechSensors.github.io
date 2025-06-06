# 3D Printed Electromechanical Sensors Performance Comparison

This repository contains interactive plots and accompanying data from the paper:

**"Advances in 3D Printed Electromechanical Sensors: Performance Comparison, Trends, and Future Directions"**

by **Anders Frem Wolstrup, Jon Spangenberg, Akio Yamamoto, Andrew Gleadall, and Gabriel Zsurzsan**.

Journal: **Additive Manufacturing** (Under Revision)

---

## Abstract

3D printing has revolutionized electromechanical sensor design, enabling rapid prototyping and complex geometries, and driving significant growth in this research field. However, as more sensors are developed using diverse printing methods and sensing mechanisms, the need for standardized reporting and comparative metrics becomes increasingly critical. Without such metrics, new sensors cannot be properly contextualized or benchmarked against the state of the art, slowing progress in the field.

This review addresses this gap by cataloguing key performance metrics from the literature, including input/output range, sensitivity, mechanical and electrical properties, and the specific 3D printing processes used, to enable meaningful comparison. These metrics are applied to quantitatively analyze 74 sensors reported across different additive manufacturing techniques. Additionally, underreported characteristics such as hysteresis, drift, and long-term stability are considered to provide a more complete assessment of sensor performance.

Beyond quantitative comparison, this review introduces a framework for categorizing sensors based not only on electrical output type (e.g., resistive, capacitive) but also on the underlying sensing basis, distinguishing whether the response arises from intrinsic material properties (e.g., quantum tunneling, percolation) or from structure-induced mechanisms (e.g., constriction resistance).

The review also highlights advances in 3D printing for electronics manufacturing to inspire future directions and concludes with six recommendations for sensor development, focusing on aligning sensing mechanisms with appropriate fabrication strategies and aiding metric standardization across the field.

---

## Repository Contents

- **Data/**: Contains CSV files used to generate the interactive plots, extracted from the literature.
- **index.html**: Interactive dashboard displaying sensor performance plots based on the dataset.
- **README.md**: This document.

---

## Interactive Plots

Explore the interactive version of the plots (Figure 7 and Figure 8 from the paper) at the following link:

🔗 [Interactive Plots on GitHub Pages](https://ElemechSensors.github.io/)

---

## Contributing

We welcome contributions to expand and refine the dataset of 3D printed electromechanical sensors.

If you would like to contribute:

1. Add your data in the same format to the appropriate `.csv` file(s) in the **`Data/`** directory (e.g., `ForceData.csv`, `PressureData.csv`, `StrainData.csv`).
2. Ensure your entries are accurate and consistent with the existing data structure.
3. Submit a pull request with a brief description of your addition.

You can also open an issue for discussion, clarification, or assistance with formatting.

---

## Note

This repository and the interactive plots webpage are currently a **proof-of-concept** implementation to demonstrate the potential for interactive data visualization of performance metrics for 3D printed electromechanical sensors.

---

For questions or further information, please contact the corresponding author or create an issue in this repository.

