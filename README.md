# AER

Code for preprint paper "Neuro-Inspired Dual Memory System for Enhanced Replay in Continual Learning".

![aer_overall](https://github.com/AlexQilong/AER/assets/108171769/7216d299-ab74-43b3-a3f6-a092e23335a0)

We extended the [Mammoth](https://github.com/aimagelab/mammoth) framework with our method AER.

## Setup

[Anaconda](https://www.anaconda.com/download) is recommended for virtual environment management.

After installation, do:
+ `conda create -n AER python=3.10.0`
+ `conda activate AER`
+ `pip install -r requirements.txt`

## Run

Example:

`python main.py --model 'er_bpcn' --buffer_size 200 --dataset 'seq-cifar100' --theta 0.1 --seed 0`
