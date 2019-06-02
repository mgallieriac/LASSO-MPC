# LASSO-MPC
Publications, Slides and PhD Thesis (2014) on the use of L1-Regularised Least Squares in Model Predictive Control. 

The University of Cambridge, UK.

## Content
* **Papers** All conference publications.
* **Slides** Some presentations given through the years.
* **Thesis** A preprint of the PhD thesis, defended in 2014. For final version see the 2016 [Springer book](https://www.springer.com/de/book/9783319279619).

### Technical results
* Proof of sparsity of control action for redundantly actuated systems
* Construction of a Terminal cost (Lyapunov function) and terminal set (Invrariant set) using set-theoretic control
* Terminal conditions for both regulation and tracking of LTI and PWA systems
* Proof of stability and intrinsic robustness using lambda-contractive sets

### Examples
* High fidelity simulation of ship roll stabilisation (achieves state of the art roll reduction with minimum use of rudder)
* Aircraft control with prioritised actuators
* Network congestion control with backup routes
* For spacecraft control with minimum thruster constraint see the [journal paper](https://www.tandfonline.com/doi/abs/10.1080/00207179.2013.789608)

# How to cite

## Conference papers
```
@inproceedings{Gallieri2012,
  doi = {10.1109/acc.2012.6315171},
  url = {https://doi.org/10.1109/acc.2012.6315171},
  year = {2012},
  month = jun,
  publisher = {{IEEE}},
  author = {M. Gallieri and J. M. Maciejowski},
  title = {$\ell_{asso}$-{MPC}: Smart regulation of over-actuated systems},
  booktitle = {2012 American Control Conference ({ACC})}
}
```

```
@inproceedings{Gallieri2013,
  doi = {10.23919/ecc.2013.6669549},
  url = {https://doi.org/10.23919/ecc.2013.6669549},
  year = {2013},
  month = jul,
  publisher = {{IEEE}},
  author = {Marco Gallieri and Jan M. Maciejowski},
  title = {Stabilising terminal cost and terminal controller for $\ell_{asso}$-{MPC}: enhanced optimality and region of attraction},
  booktitle = {2013 European Control Conference ({ECC})}
}
```

```
@inproceedings{Gallieri2013,
  doi = {10.1109/cdc.2013.6761015},
  url = {https://doi.org/10.1109/cdc.2013.6761015},
  year = {2013},
  month = dec,
  publisher = {{IEEE}},
  author = {Marco Gallieri and Jan M. Maciejowski},
  title = {Soft-constrained $\ell_{asso}$-{MPC} for robust {LTI} tracking: Enlarged feasible region and an {ISS} gain estimate},
  booktitle = {52nd {IEEE} Conference on Decision and Control}
}
```

``` 
@inproceedings{Gallieri2015,
  doi = {10.1109/ecc.2015.7330598},
  url = {https://doi.org/10.1109/ecc.2015.7330598},
  year = {2015},
  month = jul,
  publisher = {{IEEE}},
  author = {Marco Gallieri and Jan M. Maciejowski},
  title = {Model predictive control with prioritised actuators},
  booktitle = {2015 European Control Conference ({ECC})}
}
```


## Journal paper
```
@article{Hartley2013,
  doi = {10.1080/00207179.2013.789608},
  url = {https://doi.org/10.1080/00207179.2013.789608},
  year = {2013},
  month = nov,
  publisher = {Informa {UK} Limited},
  volume = {86},
  number = {11},
  pages = {2104--2113},
  author = {Edward N. Hartley and Marco Gallieri and Jan M. Maciejowski},
  title = {Terminal spacecraft rendezvous and capture with {LASSO} model predictive control},
  journal = {International Journal of Control}
}
```

## PhD Thesis/Book
```
@book{Gallieri2016,
  doi = {10.1007/978-3-319-27963-3},
  url = {https://doi.org/10.1007/978-3-319-27963-3},
  year = {2016},
  publisher = {Springer International Publishing},
  author = {Marco Gallieri},
  title = {Lasso-{MPC} {\textendash} Predictive Control with $\ell$1-Regularised Least Squares}
}
```
