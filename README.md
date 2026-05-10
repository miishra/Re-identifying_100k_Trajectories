
# YJMob100K Re-identification Framework
## ASIA CCS 2026 Artifact

This repository accompanies the paper:

> **How Tough Is Location Anonymization? Re-identifying 100K Real-User Trajectories in Japan**  
> Abhishek Kumar Mishra, Mathieu Cunche, Héber H. Arcolezi  
> ASIA CCS 2026 — 21st ACM ASIA Conference on Computer and Communications Security  
> Bangalore, India, June 2026

---

# Overview

This repository contains the experimental notebook used in our study on large-scale mobility trajectory re-identification and privacy analysis using the YJMob100K dataset.

The notebook includes:

- Spatial re-identification
- Population-density alignment
- Temporal re-identification
- Holiday and event alignment
- Privacy-risk metrics
- Home/work anchor analysis
- Trajectory unicity analysis
- Geo-Indistinguishability experiments
- Local Differential Privacy (GRR) experiments
- Spatial de-structuring analysis
- Figure generation and visualization

---

# Important Notice

This repository does **NOT** redistribute:

- the original YJMob100K dataset
- population datasets
- external geographic metadata
- public holiday files
- auxiliary event datasets

The notebook acts as a **research artifact and implementation reference** only.

Users must independently obtain all required input datasets and place them locally before running the notebook.

---

# Required Input Files

The notebook expects several input datasets and auxiliary files, including but not limited to:

```text
yjmob100k-dataset1.csv
yjmob100k-dataset2.csv
POI_datacategories.csv
cell_POIcat.csv
```

Additional external files may include:

- Japanese population density datasets
- Public holiday calendars
- Geographic metadata
- Event information

Please adapt file paths in the notebook according to your local environment.

---

# Repository Structure

```text
reid.ipynb
README.md
```

The notebook contains the complete experimental workflow.

---

# Installation

We recommend using Python 3.10+.

Install dependencies:

```bash
pip install numpy pandas scipy scikit-learn matplotlib seaborn geopandas contextily shapely pyproj tqdm numba jupyter
```

---

# Running the Notebook

Launch Jupyter:

```bash
jupyter notebook
```

Then open:

```text
reid.ipynb
```

---

# Ethical Notice

This repository is released strictly for:

- academic research
- reproducibility
- privacy evaluation
- educational purposes

The code and methods must **NOT** be used for:

- malicious deanonymization
- surveillance
- targeted tracking
- privacy attacks against individuals

No personally identifying information is redistributed in this repository.

---

# Citation

If you use this code, please cite:

```bibtex
@inproceedings{mishra2026location,
  title={How Tough Is Location Anonymization? Re-identifying 100K Real-User Trajectories in Japan},
  author={Mishra, Abhishek Kumar and Cunche, Mathieu and Arcolezi, Héber H.},
  booktitle={Proceedings of the 21st ACM ASIA Conference on Computer and Communications Security (ASIA CCS)},
  year={2026}
}
```

Reference:

> Abhishek Kumar, Mathieu Cunche, Héber H Arcolezi.  
> *How Tough Is Location Anonymization? Re-identifying 100K Real-User Trajectories in Japan.*  
> ASIACCS 2026 - 21st ACM ASIA Conference on Computer and Communications Security,  
> Jun 2026, Bangalore, India.  
> ⟨10.1145/nnnnnnn.nnnnnnn⟩  
> ⟨hal-05546595⟩

---

# License

Released for academic and research purposes only.