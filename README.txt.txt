This is Homework 3 of the course Marketing Analytics. Fall 2023.
In this Homework I have done customer Survival Analysis and worked with the Customer lifetime Value (CLV).

This are the libraries needed to run the code:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from lifelines import WeibullAFTFitter, LogNormalAFTFitter, LogLogisticAFTFitter, ExponentialFitter
# from Exponential import ExponentialAFTFitter
from lifelines.utils import k_fold_cross_validation
import seaborn as sns
import warnings


I could not import the ExponentialAFTFitter because I was not able to install Exponential library neither in VS Code nor in any notebook. 
The needed codes are still included for ExponentialAFTFitter, however they are commented.