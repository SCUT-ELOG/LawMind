# LawMind

Automated discovery of closed-form analytical solutions to partial differential equations from governing equations, without numerical data or supervision.

## Quick Start

### Environment & Installation

- Python 3.9

1. Clone repository
```
git clone https://github.com/[YourGitHubUsername]/LawMind-1.0.git
cd LawMind
```

2. Install dependencies
```
pip install -r requirements.txt
```

### Run Example

1. Run single problem

``` python
python main.py -t [table_name] -i [instance_idx]

python main.py -t table_0 -i 0
```

2. Run all problems
``` python
python main.py -a true
```


## Citation

If you use LawMind in your research or academic publications, please cite this project as follows:
```
@software{LawMind,
  author = {[Min-Yi Zheng, Shengqi Zhang, LianCheng Wu,  Jinghui Zhong, Shiyi Chen, Yew-Soon Ong]},
  title = {LawMind 1.0: A Law-Driven Framework for Autonomous Discovery of PDE Solutions},
  year = {2026},
  url = {https://github.com/[YourGitHubUsername]/LawMind-1.0},
  version = {1.0}
}
```

