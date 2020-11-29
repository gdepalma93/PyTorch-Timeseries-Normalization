# PyTorch-Timeseries-Normalization
***Deep Adaptive Input Normalization for Time Series Forecasting***

Deep Learning (DL) models can be used to tackle time series analysis tasks with great success. However, the performance of DL models can degenerate rapidly if the data are not appropriately normalized. This issue is even more apparent when DL is used for financial time series forecasting tasks, where the non-stationary and multimodal nature of the data pose significant challenges and severely affect the performance of DL models. Deep Adaptive Input Normalization (DAIN) is a simple, yet effective, neural layer, that is capable of adaptively normalizing the input time series, while taking into account the distribution of the data. DAIN is trained in an end-to-end fashion using back-propagation and can lead to significant performance improvements.

In this repository we provide an implementation of the Deep Adaptive Input Normalization (DAIN) using PyTorch. Sample data loaders to evaluate the effectiveness of the proposed method using a large-scale limit order book dataset (FI-2010 dataset) are also provided.


[DAIN WHITEPAPER](https://arxiv.org/pdf/1902.07892.pdf)   