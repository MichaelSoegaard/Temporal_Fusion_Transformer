# Temporal Fusion Transformer - NEA

<p align="center">
    <a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/-PyTorch-red?logo=pytorch&labelColor=gray"></a>
</p>
[![Python 3.8](https://img.shields.io/badge/Python-3.8-blue)](https://www.python.org/downloads/release/python-380/)

A Technical Indicator for liquid asset evaluation using a Temporal Fusion Transformer

The model I will be exploring is a transformer-based deep learning architecture that takes advantage of attention, more specifically multi-head attention in my implementation. 
Many models use ARIMA(Auto-Regressive Integrated Moving Average) but I am proposing using transformers with multi-head attention, something that I will talk about later on, to help the model ‘learn’ about the stock rather than just trying to fit a curve on it based on the last few data points. The benefits of learning allow the model to consider previous experience instead of just looking at a few, previous data points. This technique will hopefully result in a higher accuracy compared to ARIMA. Other implementations have managed an accuracy of 94%(Zolkepli and Divino, n.d.) so I will be aiming to stay within 5%. The reduced target comes down to a few factors such as limited access hardware, not enough time to optimise my program for the hardware as well a few other factors. 

