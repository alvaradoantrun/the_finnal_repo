# my_split_config (ZMK)

This repository contains a minimal ZMK config for a custom split using **nice!nano v2** boards.

- Rows: P0.09, P0.10, P1.11, P1.13, P1.15, P0.02
- Cols:  P1.06, P1.04, P0.11, P1.00, P0.24, P0.22, P0.20
- Diodes: ROW2COL
- Right = central, Left = peripheral

## Build (GitHub Actions)
Push this repo to GitHub. The included workflow will build two UF2 files as artifacts:
- `my_split_left-nice_nano_v2.uf2`
- `my_split_right-nice_nano_v2.uf2`

Flash them to the left and right halves respectively (double-tap reset to enter UF2 bootloader) and pair only the right half.
