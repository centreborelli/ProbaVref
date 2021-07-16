##  Proba-V-ref: Repurposing the Proba-V challenge for reference-aware super resolution

#### Ngoc Long Nguyen, Jérémy Anger, Axel Davy, Pablo Arias, and Gabriele Facciolo
#### IGARSS 2021 

The PROBA-V Super-Resolution challenge distributes real low-resolution image series and corresponding high-resolution targets to advance research
on Multi-Image Super Resolution (MISR) for satellite
images. However, in the PROBA-V dataset the lowresolution image corresponding to the high-resolution
target is not identified. We argue that in doing so,
the challenge ranks the proposed methods not only by
their MISR performance, but mainly by the heuristics
used to guess which image in the series is the most
similar to the high-resolution target. We demonstrate
this by improving the performance obtained by the
two winners of the challenge only by using a different reference image, which we compute following a
simple heuristic. Based on this, we propose PROBAV-REF a variant of the PROBA-V dataset, in which
the reference image in the low-resolution series is provided, and show that the ranking between the methods changes in this setting. This is relevant to many
practical use cases of MISR where the goal is to superresolve a specific image of the series, i.e. the reference
is known. The proposed PROBA-V-REF should better reflect the performance of the different methods
for this reference-aware MISR problem.

[manuscript](https://arxiv.org/pdf/2101.10200.pdf)

#### Data

The file `reference.json` contains the id of the reference image for each series of images in the training set of the [Proba-V challenge](https://kelvins.esa.int/proba-v-super-resolution/)
