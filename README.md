# End-to-End HPC Cluster Build Guide

From an empty rack to a production AI/HPC cluster with live users — hardware, fabric, storage, provisioning tools, schedulers, identity, onboarding, and monitoring, explained for a newcomer and detailed enough to actually build with.

**[Open the guide](https://pravinhpc.github.io/hpc-cluster-build/)**

## Contents

- Foundations: the HPC stack, compute & hardware, networking & fabric, storage
- Provisioning & cluster management: NVIDIA Base Command Manager, xCAT, Warewulf + OpenHPC, bare-metal + Ansible
- Scheduling, identity & onboarding: Slurm/PBS/LSF, LDAP, SSSD, user onboarding & distribution lists
- Operations: monitoring & observability, full Day 0 → Day N build walkthrough
- Deep dives: network fabrics (IB/RoCE/Slingshot/Omni-Path), CSP cluster builds (AWS/GCP/Azure/OCI), Infrastructure as Code (Terraform/Ansible/Puppet), observability internals

Sourced from public NVIDIA/AWS/GCP/Azure/OCI docs and blogs, SchedMD, OpenLDAP/SSSD/FreeIPA, Lustre/GPFS/BeeGFS, xCAT, Warewulf/OpenHPC, HashiCorp Terraform, Ansible, Puppet, Prometheus/Grafana — real URLs cited per section under "Further Reading."

## Viewing

Live site: **https://pravinhpc.github.io/hpc-cluster-build/**

To view locally, just open `index.html` in a browser — no build step required.
