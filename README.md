# STORMS microbiome checklist

This repository versions **STORMS** (Strengthening The Organization and Reporting of Microbiome Studies), a reporting checklist for human microbiome research.

- Website: <https://stormsmicrobiome.org>
- Publication: Mirzayi C, Renson A, et al. Reporting guidelines for human microbiome research: the STORMS checklist. *Nature Medicine* 27, 1885–1892 (2021). <https://doi.org/10.1038/s41591-021-01552-x>
- Published checklist files: Zenodo, [10.5281/zenodo.5703116](https://doi.org/10.5281/zenodo.5703116) (concept DOI, always the latest version)

## Status

The current published version is **v1.03**. This repository is at an early stage. Its goal is to make the checklist easier to version, cite precisely, process with software, and extend for specific research areas.

## Contents

| Path | What it is |
|---|---|
| [`versions/1.03/`](versions/1.03/) | The v1.03 checklist (Excel, Word) and analytical sample size flowcharts, exactly as published on Zenodo. See [`PROVENANCE.md`](versions/1.03/PROVENANCE.md) for DOIs, checksums and license. |

## Roadmap

Planned work is tracked in the [issues](https://github.com/waldronlab/stormsmicrobiome/issues). The recommended order is set out in [#1](https://github.com/waldronlab/stormsmicrobiome/issues/1):

1. Resolve content discrepancies in v1.03 ([#7](https://github.com/waldronlab/stormsmicrobiome/issues/7)) and decide on stable item IDs ([#2](https://github.com/waldronlab/stormsmicrobiome/issues/2)).
2. Publish a machine-readable YAML version of the checklist ([#1](https://github.com/waldronlab/stormsmicrobiome/issues/1)).
3. Define a versioning scheme and release process ([#3](https://github.com/waldronlab/stormsmicrobiome/issues/3)) and an extension mechanism for domain-specific checklists ([#4](https://github.com/waldronlab/stormsmicrobiome/issues/4)).
4. Import published versions and generate Word/CSV from the YAML ([#5](https://github.com/waldronlab/stormsmicrobiome/issues/5)); document STREAMS and produce a YAML version of it ([#6](https://github.com/waldronlab/stormsmicrobiome/issues/6)).

## STORMS or STREAMS?

**STREAMS** (Standards for Technical Reporting in Environmental and host-Associated Microbiome Studies) is a separate checklist based on STORMS. It adapts and extends STORMS for environmental, non-human-host and synthetic microbiome studies.

- **Use STORMS** for human and clinical microbiome research.
- **Use STREAMS** for environmental, non-human-host or synthetic microbiome studies.

STREAMS links:

- Website: <https://streamsmicrobiome.org>
- Publication: *Nature Microbiology* (2025), <https://doi.org/10.1038/s41564-025-02186-2>
- Guidelines (`STREAMS_Guidelines_v1.0.xlsx`): <https://doi.org/10.5281/zenodo.15014818>
- Workshop report (June 2024): <https://doi.org/10.5281/zenodo.13829669>

STREAMS is maintained by its own authors and versioned independently (currently v1.0). See [#6](https://github.com/waldronlab/stormsmicrobiome/issues/6) for plans to document how the two checklists relate.

## License

Original content in this repository is released under [CC0 1.0](LICENSE). The published checklist files under `versions/` are licensed **CC BY 4.0** by their authors; see each version's `PROVENANCE.md`.
