# Perovskene Materials Repository

Welcome to the repository for our newly designed class of materials, "Perovskene," derived from ABC3 perovskite materials.

## Overview

Perovskene is the outcome of an innovative design, utilizing the well-known bulk template with crystal symmetry P&#773;m3m. We have meticulously cleaved this template along the [001] direction to design the perovskene structures exhibiting the P3m1 symmetry, resulting in a material with promising applications in the field of optoelectronics and beyond.

## Repository Structure

Within this repository, you will find several important files that include:

- **CIF Files:** Crystallographic Information Files representing the new generation of 2D-based perovskites - Perovskene.
- **Mechanical Properties:** Data files containing information on Young's modulus, Shear modulus, stiffness constants, and elastic tensors (C11 and C12).
- **Sound Velocities:** Calculated velocities of sound propagation in longitudinal (V_l) and transverse (V_t) directions, along with their average (V_m).
- **Debye Temperature:** Files that give the calculated Debye temperature, which is crucial for understanding thermal properties.
- **Electronic Properties:** This includes data on the HSE bandgap and work function, essential parameters for electronic applications.
- **Structural Information:** Detailed files containing the lattice constants, which are fundamental to the structure of the materials.

Additionally, we have included computational tools and models:

- **Machine Learning Model (.ipynb):** A Jupyter notebook file that demonstrates standard machine learning modeling techniques to predict the lattice constant of perovskene materials.
- **Deep Neural Network (DNN) Architecture (.ipynb):** This Jupyter notebook contains a DNN architecture that is tailored for explicit structure-property exploration. It facilitates multitarget modeling of the bandgap, lattice constant, and the 2D Young's modulus, providing a robust guide for in-depth materials analysis.

## Usage

- To utilize the machine learning models, please ensure that you have the necessary Python environment and libraries installed. The `.ipynb` files can be opened and run in Jupyter Notebook or JupyterLab, which are part of the Anaconda distribution or can be installed separately.

- Researchers are encouraged to interact with the notebooks, modify the models, and use the data provided to enhance the understanding of perovskene materials and explore further applications.

- The information provided in this repository can be used for computational modeling, material analysis, or as a starting point for experimental synthesis and characterization. Researchers and developers are encouraged to explore these files to better understand the properties of Perovskene materials and to use this data for the further development of novel applications.

## Contribution

We welcome contributions from the scientific and engineering communities. If you have performed additional analyses or have suggestions for improvements, please feel free to fork this repository and submit your pull request.

## License

This repository and its content are provided under the [MIT License](LICENSE).


## Acknowledgments

This work was supported by the U.S. Department of Energy, Office of Science, Basic Energy Sciences under Award DOE-SC0024099.


## Citation

If you use the Perovskene materials data or the computational models provided in this repository for your research, please kindly acknowledge it by citing:
```latex
@Article{ekuma_synthesis,
  author = {Ekuma, Chinedu Ekuma},
    title = "{Computational synthesis of a new generation of 2D-based perovskite quantum materials}",
    journal = {APL Machine Learning},
    volume = {2},
    number = {2},
    pages = {026102},
    year = {2024},
    month = {04},
    doi = {10.1063/5.0189497},
    url = {https://doi.org/10.1063/5.0189497},
    eprint = {https://pubs.aip.org/aip/aml/article-pdf/doi/10.1063/5.0189497/19865006/026102\_1\_5.0189497.pdf},
}
```

```latex
@misc{ekuma2023perovskene,
  author       = {C. E. Ekuma},
  title        = {Perovskene Materials Data and Models [Data set]},
  year         = {2023},
  howpublished = {\url{https://github.com/gmp007/perovskene-materials}},
  note         = {GitHub Repository. Available at: \href{https://github.com/gmp007/perovskene-materials}{PerovskeneMaterialDatabase}},
}
```



## Contact

Should you have any inquiries or require further assistance, please contact us at [cekuma1@gmail.com](mailto:cekuma1@gmail.com).

Thank you for your interest in our Perovskene materials research.

