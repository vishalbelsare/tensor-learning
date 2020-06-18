# Tensor Learning (张量学习)

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Python 3.7](https://img.shields.io/badge/Python-3.7-blue.svg)
[![GitHub stars](https://img.shields.io/github/stars/xinychen/tensor-learning.svg?logo=github&label=Stars&logoColor=white)](https://github.com/xinychen/tensor-learning)

Python codes for tensor factorization, tensor completion, and tensor regression techniques with the following real-world applications:

- [**geotensor**](https://github.com/xinychen/geotensor) | Image inpainting
- [**transdim**](https://github.com/xinychen/transdim) | Spatiotemporal traffic data imputation and prediction
- Recommender systems
- [**mats**](https://github.com/xinychen/tensor-learning/tree/master/mats) | Multivariate time series imputation and forecasting

In a hurry? Please check out our contents as follows.


Our Research
---

- [**Ma**chine Learning for Multivariate **T**ime **S**eries Forecasting (**mats**)](https://github.com/xinychen/tensor-learning/tree/master/mats)

<h5 align="center"><i>Low-Rank Autoregressive Tensor Completion for Multivariate Time Series Forecasting.<br>
  [<a href="https://arxiv.org/abs/2005">arXiv</a>]</i></h5>

<p align="center">
<img align="middle" src="https://github.com/xinychen/transdim/blob/master/images/predictor-explained.png" width="666" />
</p>

Building multivariate time series forecasting tool on the well-understood Low-Rank Tensor Completion (LRTC), we develop a **Low-Rank Autoregressive Tensor Completion** to overcome the challenge of missing time series values. This model takes into account:

- autoregressive process on the matrix structure to capture local temporal states,
- and low-rank assumption on the tensor structure to capture global low-rank patterns simultaneously.

> Codes for reproducing experiments are provided in the [**../mats**](https://github.com/xinychen/tensor-learning/tree/master/mats) folder. Please open this folder to view the documentation. If you only want to see the codes directly, please open
>  - [LATC-imputer](https://nbviewer.jupyter.org/github/xinychen/tensor-learning/tree/master/mats/LATC-imputer.ipynb/)
>  - [LATC-predictor](https://nbviewer.jupyter.org/github.com/xinychen/tensor-learning/tree/master/mats/LATC-predictor.ipynb)

If you find these codes useful, please star (★) this repository.

Quick Run
---

- If you want to run the code, please
  - download (or clone) this repository,
  - open the `.ipynb` file using [Jupyter notebook](https://jupyter.org/install.html),
  - and run the code.

