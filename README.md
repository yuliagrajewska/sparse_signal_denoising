# Interpretability and Generalization in Sparse Signal Denoising

**User guide:** 

- Run the m1_den.m file on your local machine to obtain the filters and denoised signals. 
- To obtain SNR vs Rho curves: Run m3_curves_rho.m
- To obtain SNR vs Sigma curves: Run m3_cures_sigma.m

## Abstract

Convolutional Neural Networks (CNNs) have recently gained increased recognition with signal denoising tasks, however there is little insight towards understanding their inner workings. The aim of our project is to understand what a Convolutional Neural Network learns during the training process of denoising a sparse signal, and hence improve its generalization and interpretability. We perform numerous experiments and are able to identify patterns in the filters, for example: time reversal, negation and scaling. This allows us to derive and impose constraints on CNNs. The resulting networks require less training and have increased performance as well as improved generalization. This result validates our understanding of what the CNNs learn and enhances the efficiency of sparse signal denoising.

## Signal denoising

#### Noisy and Denoised signal, negated signal and time-reversed signal
![signals_ex.svg](https://github.com/yuliagrajewska/sparse_signal_denoising/blob/main/singals_ex.svg)


#### Zero error achieved
##### Constrained Network vs Unconstrained Network
![Screenshot 2022-08-09 at 12 19 50 PM](https://user-images.githubusercontent.com/88984657/183704992-ea736a4a-fcaa-4007-8488-5353a25e104d.png)

## Filter plots

#### Unconstrained CNN
![6x2_unconstrained (1)](https://user-images.githubusercontent.com/88984657/183676779-9eb63a14-533c-44e1-a85e-214bec729d07.svg)

#### Constrained CNN
![6x2_constrained (1)](https://user-images.githubusercontent.com/88984657/183676288-63be3471-b5b4-444e-878c-b10080059182.svg)

## Performance Analysis

#### SNR vs Rho
![snr_rho_1](https://user-images.githubusercontent.com/88984657/183673201-820548c8-f6a4-41d6-8ded-374dc61771cd.svg)

#### SNR vs Sigma
![snr_sigma (1)](https://user-images.githubusercontent.com/88984657/183673159-0f385d5b-e879-422b-920f-696c17530ce1.svg)
