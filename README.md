# Phonopy-Spectroscopy

Phonopy-Spectroscopy is a project to add the capability to simulate vibrational spectra to the Phonopy code.
The software package consists of a Python module, `SpectroscoPy`, along with a set of command-line scripts for working with output from Phonopy and VASP.
This project was developed by Jonathan M. Skelton, the link to the original repository is [here](https://github.com/JMSkelton/Phonopy-Spectroscopy).

## Benchmarks with Phonopy-Spectroscopy and FHI-aims
In this fork, vibrational properties of standard molecules and materials are benchmarked against experiment and an internal FHI-aims routine for generating IR/Raman spectra. A preprocessing script is provided to make all the neccesary calculations with FHI-aims to generate a BORN file. A postprocessing Jupyter notebook is provided to make the plots. 
1. [Molecules]()
2. [Materials]()
