# IPMet Radar Image Dataset

This repository provides access to a subset of the **IPMet Radar Image Dataset**, used in the paper:

**LINDE: A Lightweight Neural Network for Remote Sensing Image Denoising**  
_Rafael G. Pires, Daniel F. Silva Santos, Dênis S. Moretto, Yasmin R. Sobrinho, Pedro Henrique Crespan Ribeiro, Roberto V. Calheiros, Khan Muhammad, João Paulo Papa_  
_Submitted to IEEE Geoscience and Remote Sensing Letters (GRSL), 2025._

## 📦 Description

The **IPMet Dataset** is a real-world collection of radar images acquired by the **Meteorological Research Center of Bauru (IPMet)** at São Paulo State University (UNESP), Brazil. It was designed to support research in image restoration and denoising tasks, especially in the context of remote sensing data.

- **Data type**: Radar reflectivity images (in dBZ)
- **Resolution**: 640 × 640 pixels (Cartesian grid)
- **Projection height**: 3.5 km
- **Scan type**: PPI (Plan Position Indicator) at 0.3° antenna elevation
- **Image format**: `.png` (8-bit grayscale)

> Radar data are originally acquired in polar coordinates with uniform radial spacing and then projected to a Cartesian grid. Spatial resolution is higher near the radar site. Some artifacts may appear but are reduced through CAPPI projections.

## 📁 Folder Structure

```
IPMet-Dataset/
├── images/
│   ├── img_0001.png
│   ├── img_0002.png
│   └── ...
├── metadata.csv
├── README.md
└── LICENSE
```

The `metadata.csv` file contains additional information for each image, including acquisition location, capture timestamp, and processing date.

## 🧪 Dataset Source

The full dataset comprises **67,424 radar images** acquired between **January 1, 2022** and **January 31, 2024** by the IPMet radar system in Bauru, Brazil.

This repository contains a **subset of 4,000 representative images**, selected to ensure diversity while maintaining computational efficiency. This subset was used in the evaluation of the **LINDE** model proposed in the corresponding paper.

## 🔍 Applications

This dataset is suitable for:

- Training and evaluation of image denoising methods  
- Benchmarking lightweight models for real-world restoration  
- Studying radar noise removal under synthetic Gaussian conditions  

## 📊 Citation

If you use this dataset in your work, please cite the following:

> R. G. Pires et al., "LINDE: A Lightweight Neural Network for Remote Sensing Image Denoising," *submitted to IEEE GRSL*, 2025.  
> [GitHub Repository](https://github.com/YOUR_USERNAME/IPMet-Radar-Dataset)

## 📜 License

This dataset is made available under the terms of the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

**Contact**  
For questions or collaborations, contact:  
[r.pires@unesp.br](mailto:r.pires@unesp.br)  
[joao.papa@unesp.br](mailto:joao.papa@unesp.br)