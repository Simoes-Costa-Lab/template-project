# Project Template – Simoes-Costa Lab

This repository provides a standard structure for computational projects in the Simoes-Costa Lab.

The goal of this template is to ensure that genomics analyses are organized in a consistent and reproducible way across projects, while remaining easy to understand and modify by lab members.

The template supports projects that may integrate multiple data types, including epigenomics, RNA-seq, and single-cell datasets.

## Repository Structure

- **metadata/** – project information, sample sheets, and data location notes  
- **single_cell/** – single-cell datasets and processed objects  
- **ATAC/** – ATAC-seq inputs and outputs  
- **CUT_RUN/** – CUT&RUN inputs and outputs  
- **RNA_Seq/** – RNA-seq inputs, alignments, and count matrices  
- **workflow/** – analysis scripts and configuration files  
- **results/** – final outputs such as figures, tables, and logs  
- **notebooks/** – exploratory analyses and visualization notebooks  
- **docs/** – project documentation and notes

Large sequencing files (FASTQ, BAM, etc.) should **not be committed to GitHub**.  
Instead, store large datasets in institutional storage and document their locations in `metadata/data_locations.md`.

## Usage

To start a new project:

1. Create a new repository from this template.
2. Update `metadata/project_info.md` with project details.
3. Add analysis scripts to `workflow/`.
4. Store final outputs in `results/`.

Update this README with the project-specific description, datasets, workflows, and outputs.
