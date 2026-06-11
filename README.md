# CrCoNi NEP Potential

This repository provides a general-purpose machine-learned interatomic potential for CrCoNi alloys based on the Neuroevolution Potential (NEP) framework. The potential has been extensively validated against first-principles calculations and benchmarked on a wide range of properties, including equations of state, phonon dispersions, temperature-dependent elastic constants, short-range order, stacking-fault energies, dislocation dissociation widths, surface and defect formation energies, melting temperatures, and strain-induced phase transformations. The validation covers both elemental and alloy systems, including equiatomic and non-equiatomic compositions.

## Repository Structure

* **datasets/**: Training and validation datasets used for potential development and benchmarking.
* **model/**: NEP input files and trained model files.

## Citation

If you use the datasets or trained models provided in this repository, please cite:

```bibtex
@misc{wu2026generalpurposemachinelearnedpotentialcrconi,
      title={General-Purpose Machine-Learned Potential for CrCoNi Alloys Enabling Large-Scale Atomistic Simulations with First-Principles Accuracy},
      author={Yong-Chao Wu and Tero Mäkinen and Mikko Alava and Amin Esfandiarpour},
      year={2026},
      eprint={2603.25616},
      archivePrefix={arXiv},
      primaryClass={cond-mat.mtrl-sci},
      url={https://arxiv.org/abs/2603.25616}
}
```
