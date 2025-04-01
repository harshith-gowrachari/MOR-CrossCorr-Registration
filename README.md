## Model Order Reduction via Cross-Correlation based Snapshots Registration
These notebooks will reproduce the results presented in the article: 
```bibtex
@misc{Gowrachari2025CrossCorr,
  title = {Model Reduction for Transport-Dominated Problems via Cross-Correlation Based Snapshot Registration},
  author = {Gowrachari, Harshith and Stabile, Giovanni and Rozza, Gianluigi},
  doi = {10.48550/ARXIV.2501.01299},
  year = {2025},
  publisher = {arXiv},
  primaryclass = {Numerical Analysis (math.NA)}
}
```
This project utilizes the [EZyRB](https://github.com/mathLab/EZyRB) Python package for the construction of reduced order model. 
## EZyRB Dependencies and installation
**EZyRB** requires `numpy`, `scipy`, `sklearn`, `matplotlib`, `torch`. 
The code has been tested with Python3.5 version, but it should be compatible with
Python3. It can be installed using `pip` or directly from the source code.

### Installing from source
The official distribution is on GitHub, and you can clone the repository using
```bash
> git clone https://github.com/mathLab/EZyRB
```

To install the latest version of the package just type:
```bash
> pip install git+https://github.com/mathLab/EZyRB
```
