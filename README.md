# UK Hansard AI Contributions, 2015-2025

This repository contains a research dataset and derived results concerning UK
Parliamentary contributions about artificial intelligence, algorithms,
algorithmic systems and automation between 2015 and 2025.

The source dataset was generated from the UK Parliament Hansard Search API
(`contributions/Spoken`) and contains 3,662 deduplicated contributions. The
package includes the retrieved parliamentary text, an analysed dataset,
statistical tables, model summaries and generated figures. It does not include
the analysis source code.

## Contents

- `source_data/`: retrieved and deduplicated Hansard contributions plus an
  extraction summary.
- `analyzed_data/`: analysed records in CSV and Parquet formats.
- `result_tables/`: aggregate descriptive, topic and sentiment tables.
- `statistical_outputs/`: data-quality checks, key statistics and regression
  summaries.
- `figures/`: generated research figures.

## Scope and interpretation

The dataset was collected using keyword searches for `artificial intelligence`,
`algorithm`, `algorithmic` and `automation`. It is therefore a keyword-defined
research corpus, not a complete record of every parliamentary discussion of AI.
Topic assignments, service-area classifications and sentiment scores are
model-derived analytical outputs and should not be treated as statements by UK
Parliament or as definitive characterisations of individual speakers.

## Licensing, attribution and personal data

The parliamentary source material is subject to the Open Parliament Licence
v3.0. Required attribution, non-endorsement, warranty and personal-data notices
are provided in [`DATA_LICENSES.md`](DATA_LICENSES.md).

Names, party affiliations and speech text in this repository are taken from
public parliamentary proceedings. Users remain responsible for ensuring that
their own processing and redistribution complies with applicable data-protection
and other laws, particularly because the Open Parliament Licence does not itself
license personal data.
