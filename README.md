### Disclaimer
This is repository was originally sourced from [FAIR-Chem](https://github.com/FAIR-Chem/fairchem) and is licensed under the MIT license with copyright (c) Meta, Inc. and its affiliates.

### Purpose
This repository serves as a stable version of FAIR-Chem for dependent applications in [CHEAT](https://github.com/catalyticmaterials/cheat)

### Installation
To install fetch the repository:
```terminal
git clone https://github.com/catalyticmaterials/fairchem.git
```

We recommend creating a new conda environment by:
```terminal
cd fairchem
conda env create -f packages/env.gpu.yml
```

After environment creation install fairchem-core using:
```terminal
conda activate fairchem
pip install -e packages/fairchem-core[dev]
```
