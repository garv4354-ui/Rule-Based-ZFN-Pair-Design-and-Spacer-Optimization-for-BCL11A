# ZFN candidate pair for BCL11A (rule-based scan)

No ZFN design tool could be reached, so a candidate pair was found by scanning the 237-nt BCL11A amplicon (chr2:60,462,161-60,462,397) for GNN-GNN-GNN half-sites with a 5-7 bp spacer. **This is a candidate from a rule-based scan, not a tool output.**

Part of a four-repository project. The scanning code (`site_count.py`) lives in `genome-editors-bcl11a-comparison`.

## Contents
| Folder | What it holds |
|---|---|
| `docs/` | ZFN report PDF |
| `figures/` | Figures 16-19: UCSC gene region, 237 bp region, sequence output, designs on the sequence |
| `data/` | The 237-nt FASTA sequence and the candidate pair table |

## Key result
Left `GTGGCTGGG` (chr2:60462236-60462244) - spacer `AAGGACA` - right `GGTGCAGAA` read on the opposite strand (chr2:60462252-60462260). Finger modules are not assigned.

## Important limits
- Everything here is a computational prediction or rule-based count. Nothing was built or tested in the laboratory.
- Tools were accessed on 24 October 2026; the genome build is GRCh38/hg38.
- Tool screenshots show a faint "Activate Windows" watermark; recapture them before journal submission.

## Cite
See `CITATION.cff` (Zenodo DOI: add after the first release).
