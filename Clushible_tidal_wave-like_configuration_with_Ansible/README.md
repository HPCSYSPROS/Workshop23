# Clushible: Tidal Wave-Like Configuration with Ansible

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10223412.svg)](https://doi.org/10.5281/zenodo.10223412)

**Authors**
* Jared Baker, NSF National Center for Atmospheric Research
* John Blaas, NSF National Center for Atmospheric Research
* Jenett Tillotson, NSF National Center for Atmospheric Research

**Artifact link:**
https://github.com/NCAR/clushible

**Abstract:**
Configuration of HPC nodes is an important aspect of maintaining any HPC cluster. Our flagship HPE/Cray EX supercomputer, Derecho, is approximately 2,500 compute nodes and is susceptible to power interruptions from external factors such as lightning strike induced power sags and utility mishaps. These events challenged us to find an acceptable mean time to recovery. Ansible is our selected configuration management system but struggles with single large-scale runs of configuration despite optimizing individual runs such as tuning fork count and enabling pipelining. We needed a method to perform a large blast of configuration within a short time period to get the system back to a functional state or apply some level of remediation such as security updates. We therefore wrote a utility, Clushible, which wraps Ansible with ClusterShell's Python API to scale out the execution of Ansible that effectively took our standard full system run from multiple hours to minutes.
