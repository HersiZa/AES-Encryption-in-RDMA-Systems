# Supplementary Material for DEBS 2026 Submission

This repository/archive contains the non-proprietary supplementary material associated with the paper:

**"Securing High-Performance Data Transfers: Implementing AES Encryption in RDMA Systems"**

## Contents

- `Supplemental_Material_Plot_data_DEBS`  
  Jupyter notebook containing the available plotting code and result data used to generate the figures included in the paper.

- `README.md`  
  This document describes the contents and limitations of the supplementary material.

## Purpose

The purpose of this supplementary package is to provide the non-proprietary artifacts underlying the evaluation results reported in the paper, and to improve transparency regarding how the included figures were generated.

## What is included

The package includes:

- plotting code for the available evaluation figures
- the available result data used in those plots

## What is not included

The following artifacts are **not** included:

- the P4 switch program
- proprietary implementation details developed during the Saab master’s thesis collaboration

## Availability limitations

The implementation was developed as part of a master’s thesis collaboration with Saab. These components, including the P4 code and some associated artifacts, are proprietary Saab intellectual property and therefore cannot be publicly distributed.

## Reproducibility scope

This supplementary package supports reproducibility **to the extent permitted by artifact ownership constraints**. In particular, it allows inspection of:

- the available result data
- the plotting workflow for the included figures
- the mapping between the notebook outputs and the figures reported in the paper

However, it does **not** enable full end-to-end reproduction of the system implementation, since the proprietary switch-side implementation cannot be released.

## Mapping to the paper

The notebook corresponds to the available figures reported in the evaluation section of the paper.  
One figure is omitted because the underlying proprietary Saab-owned artifact is not available for public release.

## Notes

The evaluation in the paper is based on the setups, metrics, and tools described in the main manuscript, including throughput, packet loss, and latency measurements across baseline and experimental configurations.
