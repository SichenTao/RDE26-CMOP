# 🏆 RDE26-CMOP

![IEEE CEC 2026](https://img.shields.io/badge/IEEE%20CEC%202026-Champion-gold)
![Official Rank](https://img.shields.io/badge/Official%20Rank-1-blue)
![Track](https://img.shields.io/badge/Track-CMOPs-green)
![Language](https://img.shields.io/badge/Language-C%2B%2B%20%2B%20Python-lightgrey)

**RDE26-CMOP is the official Champion and Rank 1 winner of Competition 4-CMOPs in the IEEE WCCI 2026 / IEEE CEC 2026 Competition on Numerical Optimization Considering Accuracy and Speed.**

This repository provides the final open-source algorithm package for the constrained multi-objective optimization track.

## 🏆 Champion Result

| Item | Description |
| --- | --- |
| Achievement | Champion / Rank 1 |
| Competition | IEEE WCCI 2026 / IEEE CEC 2026 Competition on Numerical Optimization Considering Accuracy and Speed |
| Track | Competition 4-CMOPs |
| Problem class | Constrained multi-objective optimization |
| Benchmark | 15 scalable decision-space constrained multi-objective optimization problems |
| Runs | 15 independent runs per problem |
| Budget | 200000 function evaluations per problem |
| Population size | 100 |
| Dimension | 30 |
| Official source | [P-N-Suganthan/2026-CEC](https://github.com/P-N-Suganthan/2026-CEC) |

## ✨ Highlights

- 🏆 Official Champion of the CEC 2026 CMOPs track.
- ⚡ Designed for the competition setting that jointly evaluates accuracy and speed.
- 📦 Clean final algorithm package with a track-specific `main.py` entry.
- 🔬 Part of the RDE26 series that won all four CEC 2026 numerical optimization tracks.

## 🧭 RDE26 Series Navigation

| Track | Repository |
| --- | --- |
| Competition 1-BC-SOPs | [RDE26-SOP](https://github.com/SichenTao/RDE26-SOP) |
| Competition 2-CSOPs | [RDE26-CSOP](https://github.com/SichenTao/RDE26-CSOP) |
| Competition 3-BC-MOPs | [RDE26-MOP](https://github.com/SichenTao/RDE26-MOP) |
| Competition 4-CMOPs | [RDE26-CMOP](https://github.com/SichenTao/RDE26-CMOP) |

## Team

Sichen Tao, Hanyu Hu, Ruihan Zhao, Qingke Zhang, Yifei Yang, Jian Wang, Masatoshi Kawai, and Hiroyuki Takizawa.

Tohoku University-centered RDE26 research team.

## Repository Layout

| Path | Description |
| --- | --- |
| `benchmark/` | Public benchmark materials |
| `code/rde26-cmop/main.py` | Track-specific run entry |
| `code/rde26-cmop/rde_cmop_native/` | Final algorithm source |

## Requirements

- Python 3
- C++ compiler with C++17 support
- No third-party Python package is required

## Quick Start

```bash
python3 code/rde26-cmop/main.py
```

Generated outputs are written under `code/rde26-cmop/outputs/`.

## RDEx Research Line

RDE26-CMOP continues the RDEx research line from the CEC 2025 competition series to the 2026 accuracy-and-speed competition setting.

- RDEx-CMOP 2025: [arXiv:2604.03708](https://arxiv.org/abs/2604.03708)
- RDEx competition repository: [IEEE-CEC-2025-Competition-RDEx](https://github.com/SichenTao/IEEE-CEC-2025-Competition-RDEx)

## Citation

K. Qiao, X. Ban, P. Chen, K. V. Price, P. N. Suganthan, J. Liang, C. Yue, and G. Wu, "Performance comparison of CEC 2026 competition entries on numerical optimization considering accuracy and speed," IEEE WCCI/CEC 2026 competition slides.
