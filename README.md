# DS2025_diff

---

[![OSA-improved](https://img.shields.io/badge/improved%20by-OSA-yellow)](https://github.com/aimclub/OSA)

---

## Overview

DS2025_diff is designed to benchmark and compare methods for uncovering underlying equations from noisy data, enabling robust evaluation and discovery of relationships in complex datasets. The project empowers users to assess accuracy and reliability in extracting mathematical models, ultimately supporting advances in scientific data analysis and interpretation.

---

## Table of Contents

- [Core features](#core-features)
- [Installation](#installation)
- [Contributing](#contributing)
- [Citation](#citation)

---
## Core features

1. **Synthetic Data Generation for PDEs and ODEs**: Provides scripts and workflows to generate synthetic datasets for a variety of equations (Wave, KdV, Laplace, Burgers, ODE) under different noise levels, supporting robust benchmarking and evaluation of differentiation methods.
2. **Differentiation Method Evaluation**: Implements an evaluation pipeline to assess multiple differentiation techniques available in the EPDE library, comparing their accuracy through calculation of derivatives and differentiation errors on generated datasets.
3. **Equation Discovery using EPDE and SINDy**: Enables automated search and identification of governing equations from noisy data using both EPDE and SINDy algorithms, allowing comparative studies of their performance and output structures.

---

## Installation

Install DS2025_diff using one of the following methods:

**Build from source:**

1. Clone the DS2025_diff repository:
```sh
git clone https://github.com/ITMO-NSS-team/DS2025_diff
```

2. Navigate to the project directory:
```sh
cd DS2025_diff
```

---

## Contributing

- **[Report Issues](https://github.com/ITMO-NSS-team/DS2025_diff/issues)**: Submit bugs found or log feature requests for the project.

---

## Citation

If you use this software, please cite it as below.

### APA format:

    ITMO-NSS-team (2025). DS2025_diff repository [Computer software]. https://github.com/ITMO-NSS-team/DS2025_diff

### BibTeX format:

    @misc{DS2025_diff,

        author = {ITMO-NSS-team},

        title = {DS2025_diff repository},

        year = {2025},

        publisher = {github.com},

        journal = {github.com repository},

        howpublished = {\url{https://github.com/ITMO-NSS-team/DS2025_diff.git}},

        url = {https://github.com/ITMO-NSS-team/DS2025_diff.git}

    }

---
