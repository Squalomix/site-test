---
layout: default
title: Data & Tools
permalink: /data/
---

# Data & Tools

All products of the consortium, grouped by type. Detailed datasets and protocols have their own pages on this site (see "Topics" in the menu on the left); most of those pages are maintained in their own GitHub repositories, linked at the top of each page.

## Sequence data and archives

- [NCBI BioProject entry (PRJNA707598)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA707598) — sequence data produced by the consortium, deposited at NCBI
- [Squalomix sequence archive](https://treethinkers.nig.ac.jp/squalomix/) (NIG) — sequence and annotation files, with [BLAST search](https://treethinkers.nig.ac.jp/squalomix/blast/)
- [Squalomix sequence archive](https://transcriptome.riken.jp/squalomix/) (RIKEN) — the earlier archive, still online
- [Sequences](repos/sequences.md) — sequence availability guide (replaces the old page at RIKEN)

## Species data pages

- [Species](species.md) — sequencing status for the 32 species we work on, with latest publications
- [Selected species](repos/selected-species.md) — our flagship species, for which we hold data well beyond genome assemblies
- [Genome sizes](repos/c-value.md) — original genome size (C-value) data measured by the consortium
- [Karyotypes](repos/karyotype.md) — original karyotype data, the reference for validating genome assemblies
- [Genomes on a Tree (GoaT)](https://goat.genomehubs.org/search?query=long_list%3Dsqualomix&result=taxon&summaryValues=count&taxonomy=ncbi&offset=0&fields=assembly_level%2Cassembly_span%2Cc_value%2Cgenome_size%2Clong_list%2Cother_priority%2Cfamily_representative&includeEstimates=false#long_list%3Dsqualomix) — the Squalomix species list at GoaT

## Gene expression

- Gene expression profiles based on published RNA-seq data: [cloudy catshark](https://figshare.com/articles/dataset/Scyliorhinus_torazame_gene_expression_profiles_v1/20549586); [brownbanded bamboo shark](https://figshare.com/articles/dataset/Chilocyllium_punctatum_gene_expression_profiles_v1/20549634) (figshare)

## Protocols and standards

- [iconHi-C](repos/iconhi-c.md) — our inexpensive and controllable Hi-C protocol and the record of Hi-C data production ([Kadota et al., GigaScience 9: giz158](https://doi.org/10.1093/gigascience/giz158))
- [SNEG](repos/sneg.md) — phylome construction and the standardized nomenclature of elasmobranch genes (SNEG Project)
- [Repeats](repos/repeats.md) — repetitive element resources
- [Developmental staging](repos/devstage.md) — listing of developmental staging studies on chondrichthyan species
- [A technical note for Hi-C scaffolding using YaHS](https://github.com/TkNiw/Note-for-YaHS), based on our internal benchmarking by Taiki Niwa

## Our technical basis

For our previous publication in 2018, we produced all short read sequence data in-house at the DNA Analysis Facility operated inside the [Laboratory for Phyloinformatics, RIKEN BDR](https://www.bdr.riken.jp/en/research/labs/kuraku-s/). Our genome assembly also employed mate-pair reads produced with [our protocol guide 'iMate'](https://www.slideshare.net/xsighex/imate-protocol-guide-version-20).

We have released the ['iconHi-C' (inexpensive and controllable Hi-C) protocol](repos/iconhi-c.md) for versatile Hi-C data acquisition and performed Hi-C scaffolding to obtain chromosome-scale genome sequences for diverse species. The obtained sequences are validated with original high-fidelity karyotype data provided by our cell culture protocol for elasmobranchs ([Uno et al., 2020. Commun. Biol. 3: 652](https://www.nature.com/articles/s42003-020-01373-7)).

## Data use policy

Our data use policy — covering release timing, first-publication rights and the assemblies marked 'in prep.' — is stated on the [Data Use Policy](repos/data-use-policy.md) page.
