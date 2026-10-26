# ChAI-Net: Predicting Chromatin Co-Accessibility from DNA sequence

Manuscript model and data

Pre-print link awaiting...

---

## Table of contents
1. [System requirements](#1-system-requirements)
2. [Installation guide](#2-installation-guide)
3. [Demo](#3-demo)
4. [Citation and license](#6-citation-and-license)

---

## 1. System requirements

### Operating system
- Linux, Red Hat Enterprise Linux 9.5 (64-bit) (primary development and testing platform)

### Software dependencies for training
| Software | Version |
|---|---|
| Python | 3.9.22 |
| TensorFlow | 2.9.0 |
| NumPy | 1.26.4 |
| pandas | 2.2.3 |
| CUDA (GPU only) | 11.2 |

A complete list of pinned dependencies is in env folder.

### Tested versions
The software has been tested on:
- NVIDIA A30 (24 GB)
  
### Hardware
- **Required non-standard hardware:** None for the demo (runs on CPU). / A CUDA-capable NVIDIA GPU is required for training.
- **ChAI-Net analysis code tested on:** Intel Xeon Gold 6148 CPU @ 2.40 GHz (40 CPUs), 691 GB RAM

---

## 2. Installation guide

### Instructions

```bash
# 1. Clone the repository
git clone https://github.com/jlee-86/ChAI-Net.git
cd ChAI-Net

# 2. Create the analysis environment
conda env create -f ChAINet_anlaysis.yml # or training environment ChAINet_training.yml
conda activate ChAINet_anlaysis
# 


```

Model weights are located in /models/.

### Typical install time
Approximately [10 minutes] on a normal desktop computer  

---

## 3. Demo

### Make a prediction 
A small example dataset along with a Jupyter notebook is provided in `demo/` to make a prediction and compare with the target map. 

---

## 4. Citation and license

If you use this software, please cite:

```
awaiting...
```

Released under the MIT license. 

Contact: Jodi Lee, jodi.lee@gladstone.ucsf.edu
