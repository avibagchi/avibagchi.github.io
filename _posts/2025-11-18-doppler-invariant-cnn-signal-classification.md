---
layout: post
title: "Doppler Invariant CNN for Signal Classification"
date: 2025-11-18
categories: "Research"
permalink: /blogs/doppler-invariant-cnn-signal-classification/
---

## Introduction

Radio spectrum monitoring in contested environments has become increasingly critical, driving the need for reliable automatic signal classification technology. Traditional deep learning approaches have shown promise, but they face a significant limitation: existing models require brute-force Doppler augmentation during training to achieve real-world generalization. This approach not only undermines training efficiency but also reduces model interpretability.

## The Challenge

In real-world signal processing scenarios, signals are often subject to Doppler shifts—frequency changes caused by relative motion between the transmitter and receiver. Existing CNN models struggle with these shifts because they lack inherent invariance to frequency bin shifts. This forces researchers to augment training data with numerous Doppler-shifted examples, which is computationally expensive and doesn't provide theoretical guarantees about robustness.

## Our Solution

We propose a convolutional neural network (CNN) architecture with complex-valued layers that exploits convolutional shift equivariance in the frequency domain. Our key innovation is the use of **adaptive polyphase sampling (APS)** as pooling layers, followed by a global average pooling layer at the end of the network. This design establishes provable frequency bin shift invariance.

### Key Innovations

1. **Complex-Valued Layers**: By using complex-valued convolutional layers, we can better capture the phase and magnitude information in frequency-domain signals.

2. **Adaptive Polyphase Sampling (APS)**: Our pooling strategy using APS enables the network to maintain shift-equivariant properties in the frequency domain.

3. **Provable Invariance**: Unlike data augmentation approaches, our method provides theoretical guarantees about frequency bin shift invariance.

4. **Global Average Pooling**: The final global average pooling layer ensures that the network output is invariant to frequency shifts.

## Experimental Results

Using a synthetic dataset of common interference signals, our experimental results demonstrate that:

- **Consistent Performance**: Unlike a vanilla CNN, our model maintains consistent classification accuracy with and without random Doppler shifts
- **No Doppler Training Required**: The model achieves this robustness despite being trained on no Doppler-shifted examples
- **Efficiency**: By eliminating the need for extensive data augmentation, our approach is more training-efficient

## Implications

This work establishes an invariance-driven framework for signal classification that offers provable robustness against real-world effects. The method is particularly valuable for applications in:

- Radio spectrum monitoring
- Signal intelligence
- Wireless communication systems
- Defense and security applications

The theoretical guarantees provided by our approach make it more reliable and interpretable than data augmentation-based methods.

## Future Directions

Future work could explore:
- Extension to other types of signal transformations beyond Doppler shifts
- Application to real-world signal datasets
- Integration with other signal processing techniques
- Optimization for real-time deployment

## Paper

Our paper is available on arXiv:

<a href="https://arxiv.org/abs/2511.14640" target="_blank">Doppler Invariant CNN for Signal Classification (arXiv:2511.14640)</a>

## Authors

This work is a collaboration between researchers at MIT Lincoln Laboratory.

---

*This blog post summarizes our recent work on Doppler-invariant signal classification. For technical details, please refer to the full paper linked above.*

