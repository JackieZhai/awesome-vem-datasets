# Contributing

Thanks for helping keep this list useful. New datasets, new releases of existing ones, corrections, and dead-link reports are all welcome as an [issue](https://github.com/JackieZhai/awesome-vem-datasets/issues) or a [pull request](https://github.com/JackieZhai/awesome-vem-datasets/pulls).

## What belongs here

* **Datasets** acquired with volume electron microscopy (SBEM, FIB-SEM, GCIB-SEM, ATUM-SEM, multibeam SEM, ssTEM/TEMCA/autoTEM, serial-section ET, …) that anyone can view or download: raw image volumes, segmentations, synapse maps, proofread connectomes, or ground truth.
* **Benchmarks and challenges** built on vEM data, and the **pre-training corpora** used to train foundation models on it.
* **Papers** that describe one of the datasets above (they go into [REFERENCE.md](REFERENCE.md)), plus reviews and methods that are essential for understanding them.
* Non-EM connectomics (X-ray nanotomography, expansion microscopy) only as clearly marked context, not as dataset rows.

A dataset whose data cannot be accessed (not even through a viewer) can be listed, but please say so in the *Note* column.

## Where to put things

| You want to add | File | Section |
|:--|:--|:--|
| A raw or reconstructed vEM volume | [DATASET.md](DATASET.md) | the table for its organism (or *Benchmark Cubes*, *Cell Biology*) |
| Labeled data for training/evaluating models | [README.md](README.md#accessible-ground-truth) | *Accessible Ground Truth* |
| A challenge or benchmark with a leaderboard | [README.md](README.md#benchmarks-and-challenges) | *Benchmarks and Challenges* |
| The paper behind a dataset | [REFERENCE.md](REFERENCE.md) | the heading for its publication year |
| A data portal, viewer or analysis tool | [README.md](README.md#data-portals-and-tools) | *Data Portals and Tools* / *Related Code* |
| A review or perspective | [README.md](README.md#reviews) | *Reviews* |
| A lab or company that produces vEM data | [GROUP.md](GROUP.md) | alphabetical within its category |

## Conventions

* **Units**: volume size in µm (x × y × z, e.g. `250x250x250`; use mm<sup>3</sup> for whole brains), voxel size in nm (x × y × z, e.g. `4x4x40`).
* **Numbers**: comma thousands separators (`139,255 neurons`); say what the number counts (neurons, cells, synapses, skeletons, instances).
* **Microscopy**: use the abbreviations defined in [BACKGROUND.md](BACKGROUND.md#imaging-techniques) (e.g. `SBEM`, `FIB-SEM`, `mSEM`, `ssTEM (GridTape)`).
* **Order**: newest first within a table; references newest first within a year.
* **Links**: link the data itself (portal, bucket, DOI of the data deposit) in *Link*, and the paper via [REFERENCE.md](REFERENCE.md) in *Reference*, using relative links such as `REFERENCE.md#2025` so they also work in forks.
* **Preprints**: mark them as `(preprint)` and update the entry once the paper is published.
* Leave a cell empty rather than guessing; cite the source of any number you add.

## Checklist for a pull request

- [ ] The data link opens (or the note says how to request access).
- [ ] The paper is in [REFERENCE.md](REFERENCE.md) with a DOI link.
- [ ] Units and abbreviations follow the conventions above.
- [ ] The HTML tables still render (preview the Markdown before submitting).
