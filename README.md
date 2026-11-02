# deanbittker.com

Static site served by GitHub Pages — edit `index.html` and push to `main`.

- `structures/` — trimmed PDB files (backbone + bound chemical + binding-pocket side chains):
  `gfp.pdb` (1EMA, GFP S65T + chromophore), `sh3.pdb` (2VWF, GRB2 C-SH3 + peptide),
  `mers.pdb` (AlphaFold 3 prediction of the MERS-CoV E pentamer, backbone only; B-factor = pLDDT).
- `vendor/` — [3Dmol.js](https://3dmol.csb.pitt.edu) 2.5.5 (BSD-3), self-hosted.
- To add a protein: drop a PDB in `structures/` and add an entry to `PROTEINS` in `index.html`.
