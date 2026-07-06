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

| Result | Track | Repository |
| --- | --- | --- |
| 🏆 Champion / Rank 1 (sum/RS: 277418/75) | Competition 1-BC-SOPs | [RDE26-SOP](https://github.com/SichenTao/RDE26-SOP) |
| 🏆 Champion / Rank 1 (sum/RS: 192754/55) | Competition 2-CSOPs | [RDE26-CSOP](https://github.com/SichenTao/RDE26-CSOP) |
| 🏆 Champion / Rank 1 (sum/RS: 87261.5/16) | Competition 3-BC-MOPs | [RDE26-MOP](https://github.com/SichenTao/RDE26-MOP) |
| 🏆 Champion / Rank 1 (sum/RS: 188840/38) | Competition 4-CMOPs | [RDE26-CMOP](https://github.com/SichenTao/RDE26-CMOP) |

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

## 🔗 RDEx 2025 Research Line

The RDE26 series continues the RDEx research line from the CEC 2025 numerical optimization competition series to the 2026 accuracy-and-speed competition setting.

### RDEx 2025 Navigation

| Result | Track | Repository | Paper |
| --- | --- | --- | --- |
| 🥇 Rank 1 U-score (total: 81229.5) | CEC 2025 BC-SOPs | [RDEx_SOP](https://github.com/SichenTao/IEEE-CEC-2025-Competition-RDEx/tree/main/RDEx_SOP) | [arXiv:2603.27089](https://arxiv.org/abs/2603.27089) |
| 🥇 Rank 1 U-score (total: 53680.5) | CEC 2025 BC-CSOPs | [RDEx_CSOP](https://github.com/SichenTao/IEEE-CEC-2025-Competition-RDEx/tree/main/RDEx_CSOP) | [arXiv:2603.27090](https://arxiv.org/abs/2603.27090) |
| 🥇 Rank 1 U-score (total: 36343.5) | CEC 2025 BC-MOPs | [RDEx_MOP](https://github.com/SichenTao/IEEE-CEC-2025-Competition-RDEx/tree/main/RDEx_MOP) | [arXiv:2603.27092](https://arxiv.org/abs/2603.27092) |
| 🥇 Rank 1 U-score (total: 58456.0) | CEC 2025 BC-CMOPs | [RDEx_CMOP](https://github.com/SichenTao/IEEE-CEC-2025-Competition-RDEx/tree/main/RDEx_CMOP) | [arXiv:2604.03708](https://arxiv.org/abs/2604.03708) |

### RDEx 2025 Paper Citations

1. Sichen Tao, Yifei Yang, Ruihan Zhao, Kaiyu Wang, Sicheng Liu, and Shangce Gao, "RDEx-SOP: Exploitation-Biased Reconstructed Differential Evolution for Fixed-Budget Bound-Constrained Single-Objective Optimization," arXiv:2603.27089, 2026. DOI: [10.48550/arXiv.2603.27089](https://doi.org/10.48550/arXiv.2603.27089).
2. Sichen Tao, Yifei Yang, Ruihan Zhao, Kaiyu Wang, Sicheng Liu, and Shangce Gao, "RDEx-CSOP: Feasibility-Aware Reconstructed Differential Evolution with Adaptive epsilon-Constraint Ranking," arXiv:2603.27090, 2026. DOI: [10.48550/arXiv.2603.27090](https://doi.org/10.48550/arXiv.2603.27090).
3. Sichen Tao, Yifei Yang, Ruihan Zhao, Kaiyu Wang, Sicheng Liu, and Shangce Gao, "RDEx-MOP: Indicator-Guided Reconstructed Differential Evolution for Fixed-Budget Multiobjective Optimization," arXiv:2603.27092, 2026. DOI: [10.48550/arXiv.2603.27092](https://doi.org/10.48550/arXiv.2603.27092).
4. Sichen Tao, Yifei Yang, Ruihan Zhao, Kaiyu Wang, Sicheng Liu, and Shangce Gao, "RDEx-CMOP: Feasibility-Aware Indicator-Guided Differential Evolution for Fixed-Budget Constrained Multiobjective Optimization," arXiv:2604.03708, 2026. DOI: [10.48550/arXiv.2604.03708](https://doi.org/10.48550/arXiv.2604.03708).

<details>
<summary>BibTeX</summary>

```bibtex
@misc{tao2026rdexsop,
  title = {RDEx-SOP: Exploitation-Biased Reconstructed Differential Evolution for Fixed-Budget Bound-Constrained Single-Objective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27089},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27089}
}

@misc{tao2026rdexcsop,
  title = {RDEx-CSOP: Feasibility-Aware Reconstructed Differential Evolution with Adaptive epsilon-Constraint Ranking},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27090},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27090}
}

@misc{tao2026rdexmop,
  title = {RDEx-MOP: Indicator-Guided Reconstructed Differential Evolution for Fixed-Budget Multiobjective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27092},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27092}
}

@misc{tao2026rdexcmop,
  title = {RDEx-CMOP: Feasibility-Aware Indicator-Guided Differential Evolution for Fixed-Budget Constrained Multiobjective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2604.03708},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2604.03708}
}
```

</details>

## Citation

K. Qiao, X. Ban, P. Chen, K. V. Price, P. N. Suganthan, J. Liang, C. Yue, and G. Wu, "Performance comparison of CEC 2026 competition entries on numerical optimization considering accuracy and speed," IEEE WCCI/CEC 2026 competition slides.
