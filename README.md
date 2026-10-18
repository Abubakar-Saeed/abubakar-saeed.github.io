# abubakar-saeed.github.io

Source for [abubakar-saeed.github.io](https://abubakar-saeed.github.io) — an
in-browser demonstration of the BioGraphX constraint-graph encoding.

Paste a protein sequence and the page builds the interaction graph live: nodes
coloured by residue chemistry, arcs where two residues are chemically
compatible and close enough along the chain, and a per-residue weighted-degree
profile underneath. Hovering a residue isolates its interactions and shows the
features it carries.

Everything runs client-side. No sequence leaves the browser, and there are no
dependencies beyond a web font.

## What this is and is not

A **simplified** demonstration: five interaction rules and six descriptors,
against twelve rules and 158 features in the published encoder. It is written
to show the mechanism, not to reproduce the paper's results.

Method: Saeed A., Abbas W., *BioGraphX: Bridging the Sequence–Structure Gap via
Physicochemical Graph Encoding for Interpretable Subcellular Localization
Prediction*, **Bioinformatics Advances** (OUP), 2026.
[`10.1093/bioadv/vbag181`](https://doi.org/10.1093/bioadv/vbag181)

## Local use

Open `index.html` in a browser. There is no build step.
