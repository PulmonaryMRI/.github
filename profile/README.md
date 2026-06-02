# Pulmonary MRI GitHub Organization

Welcome to the **Pulmonary MRI** GitHub organization! The purpose of this organization is to provide a centralized resource of software repositories supporting the development and use of pulmonary (lung) MRI.  We develop open-source tools for pulmonary (lung) MRI acquisition, reconstruction, and analysis, with a focus on motion compensation and functional imaging.

## 🫁 About Us

This effort is led by MRI researchers dedicated to advancing pulmonary MRI techniques.  The scope of the repositories is intended to support any pulmonary MRI methods, including (but not limited to)
image reconstruction algorithms, motion management strategies, pulse sequences, structural imaging methods, functional lung imaging methods, and hyperpolarized gas (e.g. Xe-129) methods.

## 🔬 Research Areas

- **Motion Management** — algorithms that correct for respiratory motion during acquisition
- **Ultrashort echo time (UTE) imaging** — techniques for imaging the lung parenchyma
- **1H functional lung MRI** — ventilation/perfusion mapping
- **Hyperpolarized 129Xe imaging** — functional imaging of ventilation and gas exchange
- **Reproducible research** — code and data sharing to support open science

## 📦 Repositories

### Motion Management

| Repository | Description | Language | Reference |
|---|---|---|---|
| [imoco_recon](https://github.com/PulmonaryMRI/imoco_recon) | Iterative Motion Compensation (iMoCo) reconstruction for MRI | MATLAB & Python versions | [doi:10.1002/mrm.27998](https://doi.org/10.1002/mrm.27998) |
| [MoCoLoR](https://github.com/PulmonaryMRI/MoCoLoR) | Motion-compensated low-rank reconstruction for simultaneous structural and functional UTE lung MRI | Python | [doi:10.1002/mrm.29703](https://doi.org/10.1002/mrm.29703) |
| [pulmonary-MRI-reconstruction](https://github.com/PulmonaryMRI/pulmonary-MRI-reconstruction) | Tools for reconstructing pulmonary MRI datasets to manage motion | MATLAB | [doi:10.1002/mrm.26958](https://doi.org/10.1002/mrm.26958) |
| [philips_recon](https://github.com/PulmonaryMRI/philips_recon) | Scripts for reconstructing pulmonary UTE MRI acquired on Philips scanners | Jupyter Notebook | - |
| [MostMoCo](https://github.com/DingZeKang/MostMoCo) | Motion-state weighted motion-compensation reconstruction for dynamic pulmonary UTE MRI | MATLAB | [doi:10.1002/mrm.29204](https://doi.org/10.1002/mrm.29204) |
| [selfgated_noncartesian_reconstruction](https://github.com/NHLBI-MR/selfgated_noncartesian_reconstruction) | Self-gated 3D stack-of-spirals UTE pulmonary MRI reconstruction at 0.55T | C++ | [doi:10.1002/mrm.29079](https://doi.org/10.1002/mrm.29079) |
| [icomoco](https://github.com/NHLBI-MR/icomoco) | Gadgetron implementation of iCoMoCo reconstruction | C++ | [doi:10.1002/mrm.30054](https://doi.org/10.1002/mrm.30054) |
| [extreme_mri](https://github.com/PulmonaryMRI/extreme_mri) | Scripts to reproduce Extreme MRI experiments, including lung reconstruction demos | Python | [arXiv:1909.13482](https://arxiv.org/abs/1909.13482) |


### Pulse Sequences

| Repository | Description | Language | Reference |
|---|---|---|---|
| [replication_bstar](https://github.com/usc-mrel/replication_bstar) | Open-source replication of the bSTAR sequence with Pulseq and BART reconstruction tools | MATLAB | [doi:10.1002/mrm.29947](https://doi.org/10.1002/mrm.29947) |

### 1H Functional Imaging

| Repository | Description | Language | Reference |
|---|---|---|---|
| [MoCoLoR](https://github.com/PulmonaryMRI/MoCoLoR) | Motion-compensated low-rank reconstruction for simultaneous structural and functional UTE lung MRI | Python | [doi:10.1002/mrm.29703](https://doi.org/10.1002/mrm.29703) |
| [reproducibility](https://github.com/PulmonaryMRI/reproducibility) | Scripts for a pulmonary ventilation analysis reproducibility study using UTE lung MRI | Python | [doi:10.1101/2023.10.22.563196](https://doi.org/10.1101/2023.10.22.563196) |
| [dynamic_lung_water](https://github.com/NHLBI-MR/dynamic_lung_water) | Dynamic lung water magnetic resonance imaging during exercise stress | Matlab/Python | [doi:10.1002/mrm.29716](https://doi.org/10.1002/mrm.29716) |

### Hyperpolarized Xenon

| Repository | Description | Language | Reference |
|---|---|---|---|
| [XIPline](https://github.com/aboodbdaiwi/XIPline) | Open-source graphical pipeline for hyperpolarized 129Xe MRI analysis | MATLAB | [doi:10.1002/mrm.30347](https://doi.org/10.1002/mrm.30347) |
| [xenon-segmentation](https://github.com/junlanlu/xenon-segmentation) | Deep learning segmentation library for xenon MRI images | Python | [doi:10.1016/j.mri.2023.07.001](https://doi.org/10.1016/j.mri.2023.07.001) |
| [XenonMRI](https://github.com/thePIRL/XenonMRI) | Analyze 129Xenon MRI data | Python | [doi:10.1002/mrm.28985](https://doi.org/10.1002/mrm.28985) |

## 🌐 Related GitHub Organizations

- [TeamXenonDuke](https://github.com/TeamXenonDuke)
- [thePIRL](https://github.com/thePIRL):  University of Missouri PIRL (Pulmonary Imaging Research Lab)
- [NHLBI-MR](https://github.com/NHLBI-MR)
- [Xe-MRI-CTC](https://github.com/Xe-MRI-CTC): The 129Xe MRI Clinical Trials Consortium

## 🤝 Contributing

We welcome contributions! Please open an issue or pull request in the relevant repository.
