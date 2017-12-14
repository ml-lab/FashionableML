# FashionableML
Deposit for reproducibility study of the paper "Three Factors Influencing Minima in SGD" as submitted to ICLR 2018 (https://openreview.net/forum?id=rJma2bZCW).

Reproducibility study completed by Shenyang Huang, Kaylee Kutschera, and Sacha Perry-Fagant.

Project Presentation:

https://docs.google.com/presentation/d/1d9oEmbm5fWb1WReUxb7EsKWXHjWrcmHX5LGxRCNc7E8/edit?usp=sharing

Instruction:
1. Controllable noise

run 20ReluNN.py

2. Memorization

Using python3.5:

run tf_mlp.py

The parameters can be changed on lines 42, 55, and 57.

3. CLR

open jupyter notebook

run CLRFashionMNIST.ipynb

Dependencies:

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

import tensorflow as tf

import random

from \__future\__ import print_function

import copy
