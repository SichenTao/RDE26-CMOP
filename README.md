# RDE26-CMOP

RDE26-CMOP is the Rank 1 entry for Competition 4-CMOPs in the IEEE WCCI 2026 / IEEE CEC 2026 Competition on Numerical Optimization Considering Accuracy and Speed.

## Competition

| Item | Description |
| --- | --- |
| Track | Competition 4-CMOPs |
| Problem class | Constrained multi-objective optimization |
| Benchmark | 15 scalable decision-space constrained multi-objective optimization problems |
| Runs | 15 independent runs per problem |
| Budget | 200000 function evaluations per problem |
| Population size | 100 |
| Dimension | 30 |
| Official rank | Rank 1 |
| Official source | [P-N-Suganthan/2026-CEC](https://github.com/P-N-Suganthan/2026-CEC) |

## Authors

Sichen Tao, Hanyu Hu, Ruihan Zhao, Qingke Zhang, Yifei Yang, Jian Wang, Masatoshi Kawai, and Hiroyuki Takizawa.

## Contents

| Path | Description |
| --- | --- |
| `benchmark/` | Public benchmark materials |
| `code/rde26-cmop/main.py` | Track-specific run entry |
| `code/rde26-cmop/rde_cmop_native/` | Final algorithm source |

## Requirements

- Python 3
- C++ compiler with C++17 support

## Run

```bash
python3 code/rde26-cmop/main.py
```

Generated outputs are written under `code/rde26-cmop/outputs/`.

## Reference

K. Qiao, X. Ban, P. Chen, K. V. Price, P. N. Suganthan, J. Liang, C. Yue, and G. Wu, "Performance comparison of CEC 2026 competition entries on numerical optimization considering accuracy and speed," IEEE WCCI/CEC 2026 competition slides.
