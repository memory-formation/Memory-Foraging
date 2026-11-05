# Code

One notebook per Results section, reading the anonymised data in `../Data`. The stored outputs
are the results reported in the paper.

| notebook | Results section | figure |
|---|---|---|
| `results1_individual_recall.ipynb` | 1 | Figure 2 |
| `results2_collaborative_patches.ipynb` | 2 | Figure 3a–b |
| `results3_first_handover_cost.ipynb` | 3 | Figure 3 |
| `results4_category_competition.ipynb` | 4 | Figure 3e |
| `results5a_later_recall.ipynb`, `results5b_patch_depth.ipynb` | 5 | Figure 4 |
| `figure1_schematic.ipynb` | – | Figure 1 |

Install the packages with `pip install -r requirements.txt` (Python 3.11), then run the notebooks
in the order 1, 2, 4, 3, 5a, 5b, since later notebooks read tables written by earlier ones (section
3 quotes two numbers computed in section 4). Outputs are written to `Code/_output/`.


