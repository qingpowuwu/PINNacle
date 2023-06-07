# PINNacle

This repository is our codebase for PINNacle: A Comprehensive Benchmark of
Physics-Informed Neural Networks for Solving PDEs.

Our NIPS paper is currently under review. We will provide more detailed guide soon.

## Installation

```shell
# install torch manually
# install other dependencies
pip install -r requirements.txt
```

## Usage

Run all 22 cases with default settings:

```shell
python benchmark.py [--name EXP_NAME] [--seed SEED] [--device DEVICE]
```

Please read the comments in `benchmark.py` to modify the experiment configuration and apply different methods.

### Multi-GPU Training

One can use `--device` to specify the GPU devices to use. If more than one GPU is specified, the program will run multiple experiments in parallel.
