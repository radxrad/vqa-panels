# Viral Quality Assurance Panels Used by RADx-rad Projects

This repository contains the following data for inactivated viruses used by the NIH COVID-19 [RADx-rad](https://www.nih.gov/research-training/medical-research-initiatives/radx/radx-programs#radx-rad) initiative for method benchmarking and validation.

| Resource | Description |
|----------|-------------|
| [Inactivated Virus Metadata](RADx-rad_inactivated_virus_metadata.csv) | Includes virus ID, lineage, source, inactivation method, concentration, and growth conditions. |
| [Material Safety Data Sheets (MSDS)](msds) | Safety documentation for handling each inactivated virus batch. |

### Inactivated Virus Metadata

- **Virus Identification:**  
  `virus_batch_number`, `virus_shortname`, `isolate_name`, `gisaid_id`, `nucleotide_db_id`, `pango_lineage`, `who_label`, `gisaid_clade`

- **Organism Details:**  
  `target_organism_name`, `target_organism_taxonomy_id`

- **Source & Collection Info:**  
  `virus_sample_source`, `virus_sample_source_url`, `virus_source`, `virus_location`, `virus_sample_type`, `virus_sample_grow_cell_line`

- **Inactivation & Formulation:**  
  `virus_sample_inactivation_method`, `virus_sample_formulation`

- **Quantification Metadata:**  
  `virus_sample_concentration`, `virus_sample_concentration_unit`, `virus_sample_concentration_reference_gene`,,  
  `virus_sample_genome_equivalents`, `virus_sample_genome_equivalents_unit`, `virus_sample_genome_equivalents_reference_gene`,  
  `virus_preinactivation_tcid50`, `virus_preinactivation_tcid50_unit`


## 📝 Citation

RADx-Rad Discoveries & Data: Consortium Coordination Center Program Organization (UCSD), Viral Quality Assurance Panels Used by RADx-rad Projects, Available online: [https://github.com/radxrad/vqa-panels](https://github.com/radxrad/vqa-panels) (2025)

---

## 💰 Funding

Supported by the **Office of the Director, National Institutes of Health** under:

> **RADx-Rad Discoveries & Data: Consortium Coordination Center Program Organization**  
> [Grant: 7U24LM013755](https://reporter.nih.gov/project-details/10745886)