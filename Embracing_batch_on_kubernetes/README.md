# Embracing Batch on Kubernetes

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10223341.svg)](https://doi.org/10.5281/zenodo.10223341)

**Authors**
* Jason Kincl, Redhat, Inc
* Patrick Bruszewski, Redhat, Inc


**Abstract:**
As the adoption of Kubernetes continues to grow, there is an increasing demand for performing larger scale batch processing using Kubernetes. Much of the initial workloads are around machine learning but there is also interest in converging traditional HPC and Kubernetes clusters for operational efficiencies.
In this talk, we want to look at how we can leverage both traditional HPC workload partitioning as well as features of Kubernetes to achieve a hybrid system that can be used for all types of workloads. We will show how we isolate the orchestration and user processes in Kubernetes allowing for maximum use of the hardware for running batch workloads with benchmark comparisons against a traditional HPC cluster.
