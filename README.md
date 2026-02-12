# IPMet Radar Image Dataset

This repository provides access to a subset of the **IPMet Radar Image Dataset**.

## 📦 Description

The **IPMet Dataset** is a real-world collection of radar images acquired by the **Meteorological Research Center of Bauru (IPMet)** at São Paulo State University (UNESP), Brazil. It was designed to support research on image restoration and denoising, particularly for remote sensing data.

- **Data type**: Radar reflectivity images (in dBZ)
- **Resolution**: 640 × 640 pixels (Cartesian grid)
- **Projection height**: 3.5 km
- **Scan type**: PPI (Plan Position Indicator) at 0.3° antenna elevation
- **Image format**: `.png` (8-bit grayscale)

> Radar data are originally acquired in polar coordinates with uniform radial spacing and then projected to a Cartesian grid. Spatial resolution is higher near the radar site. Some artifacts may appear, but are reduced through CAPPI projections.

## 📁 Folder Structure

```
IPMet-Dataset/
├── images/
│   ├── img_0001.png
│   ├── img_0002.png
│   └── ...
├── README.md
└── LICENSE
```

## 🧪 Dataset Source

The full dataset comprises **67,424 radar images** acquired between **January 1, 2022** and **January 31, 2024** by the IPMet radar system in Bauru, Brazil.

This repository contains a **subset of 4,000 representative images**, selected to ensure diversity while maintaining computational efficiency. 

## 🔍 Applications

This dataset is suitable for:

- Training and evaluation of image denoising methods  
- Benchmarking lightweight models for real-world restoration  
- Studying radar noise removal under synthetic Gaussian conditions  

## 📊 Citation

If you use this dataset in your work, please cite the following paper:

R. G. Pires, D. F. S. Santos, R. V. Calheiros, J. P. Papa, I. H. Lee, S. Bakshi, and K. Muhammad, “A Convolutional Recurrent Mixer Network For Radar Meteorological Image Super-Resolution,” in Proceedings of the 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Hyderabad, India, p. 1-5 (2025). [[bibtex](http://www.uol.com.br "UOL")]


## 📜 License

This dataset is made available under the terms of the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

**Contact**  
For questions or collaborations, contact:  
[r.pires@unesp.br](mailto:r.pires@unesp.br)  
[daniel.fs.santos@unesp.br](mailto:daniel.fs.santos@unesp.br) 
[joao.papa@unesp.br](mailto:joao.papa@unesp.br)
