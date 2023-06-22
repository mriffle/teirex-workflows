---
layout: default
---

Below are links to the documentation for each workflow, which include instructions for installing, running, and interpreting the output of each workflow.

## _DIA - peptide search and quantification_

This workflow runs `msconvert`, `EncyclopeDIA`, and `Skyline` to run a DIA workflow for discovering and quantifying peptides.

See: [DIA Workflow Documentation](http://nf-teirex-dia.rtfd.io/)

## _DDA - peptide search_

This workflow runs `msconvert`, `Comet`, `Percolator`, and `Limelight` to run a DDA workflow for bottom up proteomics and subsequent visualization and sharing.

See: [DDA Workflow Documentation](http://nf-teirex-dda.rtfd.io/)

## Open Modification DDA

This workflow runs `msconvert`, `Magnum`, `Percolator`, and `Limelight` to run a DDA workflow for discovery of peptides and modification or adduct masses
that may be present in the data, without _a priori_ knowledge of what masses may be present.

See: [Open Modication Workflow Documentation](http://nf-openmod-dda.rtfd.io/)

## AWS Batch

Any of these workflows may be optionally run using AWS Batch. Follow the link below for instructions to set up, configure, and run workflows using AWS Batch.

See: [Open AWS Batch Documentation](http://teirex-aws-setup.rtfd.io/)
