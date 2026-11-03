---
layout: default
title: Data & Tools
permalink: /data/
---

# Data & Tools

The sequence data reported in our publications are deposited at NCBI, under the consortium's [BioProject entry (PRJNA707598)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA707598). All products of the consortium, grouped by type, are listed below. Detailed datasets and protocols have their own pages on this site (see "Topics" in the menu on the left); most of those pages are maintained in their own GitHub repositories, linked at the top of each page.

## Our technical basis

For our previous publication in 2018, we produced all short read sequence data in-house at the DNA Analysis Facility operated inside the [Laboratory for Phyloinformatics, RIKEN BDR](https://www.bdr.riken.jp/en/research/labs/kuraku-s/). Our genome assembly also employed mate-pair reads produced with [our protocol guide 'iMate'](https://www.slideshare.net/xsighex/imate-protocol-guide-version-20).

We have released the ['iconHi-C' (inexpensive and controllable Hi-C) protocol](repos/iconhi-c.md) for versatile Hi-C data acquisition and performed Hi-C scaffolding to obtain chromosome-scale genome sequences for diverse species. The obtained sequences are validated with original high-fidelity karyotype data provided by our cell culture protocol for elasmobranchs ([Uno et al., 2020. Commun. Biol. 3: 652](https://www.nature.com/articles/s42003-020-01373-7)).

<div class="accent-bar" aria-hidden="true"></div>

## Protocols and standards

- [iconHi-C](repos/iconhi-c.md) — our inexpensive and controllable Hi-C protocol and the record of Hi-C data production ([Kadota et al., GigaScience 9: giz158](https://doi.org/10.1093/gigascience/giz158))
- [sQuantGenome](repos/c-value.md) — our qPCR-based protocol for estimating genome size, which requires no living cells
- [SNEG](repos/sneg.md) — phylome construction and the standardized nomenclature of elasmobranch genes (SNEG Project)
- [Repeats](repos/repeats.md) — repetitive element resources
- [A technical note for Hi-C scaffolding using YaHS](https://github.com/TkNiw/Note-for-YaHS), based on our internal benchmarking

<div class="accent-bar" aria-hidden="true"></div>

## Sequence data and archives

- [NCBI BioProject entry (PRJNA707598)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA707598) — sequence data produced by the consortium, deposited at NCBI
- [Selected species](repos/selected-species.md) — our flagship species, with assembly tables and the sequence availability guide (formerly the Sequences page)

<div class="accent-bar" aria-hidden="true"></div>

## Data by species

- [Species](species.md) — sequencing status for the 32 species we work on, with latest publications
- [Selected species](repos/selected-species.md) — our flagship species, for which we hold data well beyond genome assemblies
- [Genome sizes](repos/c-value.md) — original genome size (C-value) data measured by the consortium
- [Karyotypes](repos/karyotype.md) — original karyotype data, the reference for validating genome assemblies
- [Squalomix Extra](repos/extra.md) — our products on non-chondrichthyan species

<div class="accent-bar" aria-hidden="true"></div>

## Data use policy

Our data use policy — covering release timing, first-publication rights and the assemblies marked 'in prep.' — is stated on the [Data Use Policy](repos/data-use-policy.md) page.
