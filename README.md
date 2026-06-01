# Graph Cluster Trails for SIMON and SIMECK

This repository contains differential trail search results for all variants of the SIMON and SIMECK lightweight block ciphers, provided as supplementary material for research currently under review.

# Contents

- `SIMON-trails.md` — Best differential trails for SIMON32/64, SIMON48/96, SIMON64/128, SIMON96/144, and SIMON128/256
- `SIMECK-trails.md` — Best differential trails for SIMECK32/64, SIMECK48/96, and SIMECK64/128

## Notes

Trails are reported as bidirectional differential characteristics, with forward and backward round counts, total weight, and probability. Results for the largest variants exceed previously reported bounds in the literature.
All trails have been independently verified against the exact XDP^AND differential probability formula established by Biryukov, Roy, and Velichkov (FSE 2014).

## Citation

If you use these results, please cite the associated paper (reference to be added upon acceptance).
