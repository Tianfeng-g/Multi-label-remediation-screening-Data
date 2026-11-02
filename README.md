# Multi-label Remediation Technology Screening Dataset

## 1. Dataset Overview

This repository provides contaminated-site remediation project data collected from China's national construction-land soil environmental management system. The dataset was compiled from traceable engineering records, including site investigation reports, environmental risk assessments, risk-control and remediation plans, and post-remediation effectiveness assessments where available.

The source archive contains 248 unique soil-site identifiers and 161 distinct groundwater-site identifiers. The groundwater basic-information worksheet contains 173 entries, including repeated site identifiers. These records document site characteristics, contamination conditions, environmental risks, remediation technologies, and project implementation information.

For the predictive modeling analyses reported in the associated study, 168 soil sites and 105 groundwater sites with sufficiently complete information were retained. These analytical subsets are distinct from the broader source archive.

The dataset supports research on contaminated-site characteristics, remediation technology selection, and data-driven screening of candidate remediation technologies.

## 2. Dataset Description

The repository contains two Excel datasets:

- **Soil Remediation Project Dataset:** Engineering records related to contaminated soil sites.
- **Groundwater Remediation Project Dataset:** Engineering records related to contaminated groundwater sites.

Each workbook contains eight worksheets:

| Worksheet | Description |
|---|---|
| 1. Basic Site Information | Site identification, geographical information, site characteristics, and project status |
| 2. Hydrogeology & Soil Data | Soil properties, hydrogeological conditions, and environmental characteristics |
| 3. Sensitive Receptors | Nearby sensitive receptors and potential exposure conditions |
| 4. Environmental Risk Data | Contamination extent, environmental risks, and remediation requirements |
| 5. Contaminant Characteristics | Contaminant types, concentrations, physicochemical properties, and risk-related information |
| 6. Risk Control & Remediation | Risk-control and remediation plans, measures, and implementation information |
| 7. Measures and Technologies | Remediation technologies, implementation characteristics, and technology assessment information |
| 8. Effectiveness Assessment | Remediation outcomes and post-remediation assessment information |

The workbooks contain both site-level information and contaminant- or technology-level records. Multiple records may correspond to the same site. Consequently, the number of spreadsheet rows should not be interpreted as the number of independent contaminated sites.

## 3. Data Sources

The datasets were compiled from traceable contaminated-site engineering records documented in China's national construction-land soil environmental management system.

The source documents include site investigation reports, risk assessment reports, risk-control and remediation plans, and effectiveness assessment reports.

The available records vary in completeness across sites and variables. The datasets represent documented engineering projects rather than a probability sample of all contaminated sites in China.

## 4. Data Processing and Site Selection

The source datasets were organized using site identifiers to associate information across worksheets.

For the associated study, site-level information was reconstructed from the available engineering records. Sites with insufficient information for the specified predictive modeling requirements were excluded from the analytical samples.

The final modeling datasets comprise:

- **Soil:** 168 complete sites.
- **Groundwater:** 105 complete sites.

Detailed site-selection criteria, technology classification procedures, and model validation methods are described in the associated manuscript and its Supplementary Materials.

## 5. Data Availability

The source datasets are provided in this repository to facilitate academic research and improve transparency regarding contaminated-site remediation technology selection.

Users should distinguish the broader source archive from the complete-site analytical samples used for model development and evaluation.

## 6. Citation

Users of these datasets are encouraged to cite the associated research article.

The full bibliographic information will be updated following publication.
