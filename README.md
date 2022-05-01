# Machine-Failure-Prediction
Predictive maintanence (PdM) is the maintanence of machines at a predicted future time before the machine failure. This allows scheduled maintanence of the machines, reducing the unplanned downtime costs.  This repository contains deployable end-to-end classifiers to predict the probability whether a machine failure will occur or not.
Website : https://deploypredicting.herokuapp.com/

# Data
The data used in this work, taken from Maintenance.csv is available in the DATA folder. It consists of 10,000 data points stored as rows with features like UDI,Product ID, Air temperature, Process temperature, Rotational speed, Torque, Tool wear, machine failure, TWF, HDF, PWF, OSF, RNF. For simplicity, only the main failure parameter was predicted.

### Requirements

The [requirements.txt](requirements.txt) file lists all the python libraries needed to run the codes in this repository, and they can be installed using:

```shell
pip install -r requirements.txt
```



