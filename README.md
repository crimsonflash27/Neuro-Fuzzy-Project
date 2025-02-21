# Stock Price Prediction: A simple implementation of a Neuro-Fuzzy System

The repository showcases a project done for the purposes of an NTU course on
Neuro-Evolution and Fuzzy Evolution. The project is continually seeing updates
and improvements based on my review of the project work; I am hoping to iron out
a few pain points which I couldn't address due to project deadlines.

## Project Specifications

**The Neuro-Fuzzy Model used:** Attention based LSTM
**Stock Data 1:** Telsa
**Stock Data 2:** Hyundai Glovis

**Returns Calculation:** A Simple Moving Average based trading methodology is used, where a buy signal is given if Fast-SMA becomes higher than Slow-SMA. 

**Fuzzy Membership Functions:** The Gaussian Membership Functions are created with the Learning Vector Quantization (LVQ) algorithm.

The overall goal of the project was to design a Neuro-Fuzzy system that will predict stock price t time steps ahead. Using the predicted stock prices, can we make a higher return as compared to the Random Walk model ? Additionally, is Transfer Learning effective in this problem ? 



