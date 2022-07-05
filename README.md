# Improving detection of scanning attacks on heterogeneous networks with Federated Learning [WAIN 2021](https://www.performance2021.deib.polimi.it/wain/)

DOI: [10.1145/3543146.3543172](https://dl.acm.org/doi/abs/10.1145/3543146.3543172)

The source code for reproductibility of WAIN 2021 [paper](http://www.performance2021.deib.polimi.it/wp-content/uploads/2021/10/WAIN_2021_paper_14_deCarvalhoBertoli.pdf): 

Improving detection of scanning attacks on heterogeneous networks with Federated Learning, see the paper presentation:

[![Watch the video](https://img.youtube.com/vi/hV0CMnykNVk/0.jpg)](https://www.youtube.com/watch?v=hV0CMnykNVk)


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
@article{10.1145/3543146.3543172,
  author = {de Carvalho Bertoli, Gustavo and Pereira J\'{u}nior, Louren\c{c}o Alves and Saotome, Osamu},
  title = {Improving Detection of Scanning Attacks on Heterogeneous Networks with Federated Learning},
  year = {2022},
  issue_date = {March 2022},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  volume = {49},
  number = {4},
  issn = {0163-5999},
  url = {https://doi.org/10.1145/3543146.3543172},
  doi = {10.1145/3543146.3543172},
  journal = {SIGMETRICS Perform. Eval. Rev.},
  month = {jun},
  pages = {118–123},
  numpages = {6},
}
```
