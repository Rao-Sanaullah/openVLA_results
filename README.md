# OpenVLA — Robotis SG2 AI Worker Results

Simulation study of closed-loop VLA control for dual-arm humanoid manipulation using OpenVLA, deployed on the Robotis SG2 AI Worker in NVIDIA IsaacLab.

Full results, videos, and methodology: https://rao-sanaullah.github.io/openVLA_results/
For Instalation Guide: https://rao-sanaullah.github.io/OpenVLA/

## Key results

| Metric | Checkpoint | Value | Trials |
|--------|-----------|-------|--------|
| Reach success | 100k steps | 100% | 50 |
| Grasp success | 100k steps | 100% | 50 |
| Place success | 100k steps | 0% | 50 |
| Offline NormMAE | 100k steps | 1.0% | 300 samples |

OpenVLA reaches and grasps the object reliably but freezes in the visually near-static post-grasp phase, yielding 0% place success despite achieving the lowest offline prediction error of any model in the study — the sharpest instance of the offline vs. closed-loop disconnect.

## Links

- [Full results page](https://rao-sanaullah.github.io/OpenVLA/)
- [Installation guide](https://rao-sanaullah.github.io/OpenVLA/)
- [Official OpenVLA repo](https://github.com/openvla/openvla)
- [Paper](#)
