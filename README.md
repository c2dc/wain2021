# Improving detection of scanning attacks on heterogeneous networks with Federated Learning [WAIN 2021](https://www.performance2021.deib.polimi.it/wain/)
The source code for reproductibility of [WAIN 2021](https://www.performance2021.deib.polimi.it/wain/) paper: 

Improving detection of scanning attacks on heterogeneous networks with Federated Learning

## Description of the notebooks
> `Federated Learning.ipynb` - All data wrangling for the federated learning experiment reported on the paper. With 13 agents (data silos) comparing local trained models to federated learning using `FedAvg`.
> 
> `Centralized.ipynb` - Evaluation of naive scanning attack detection learning task centralizing all the data.

---
## How to run
All dependecies for running these notebooks are available on the `requirements.txt` file. Using python with virtualenv to setup the environment on Linux and access the notebooks:

```
$ python -m venv venv
$ source venv\bin\activate
(venv) $ pip install -r requirements.txt
(venv) $ jupyter notebook
```
## How to contribute
Use the [pull request](https://github.com/c2dc/wain2021/pulls) and [issues](https://github.com/c2dc/wain2021/issues) tab on this repository to contribute.

## Citing
```
TBD.
```
