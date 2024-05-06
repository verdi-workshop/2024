---
name: 'On improving the robustness of convolutional neural networks using in-parameter zero-space error correction codes'
categories:
  - Invited Talks
speakers:
  - Juan Carlos Ruiz
---


Convolutional neural networks (CNNs) are currently of great interest in critical domains demanding image classification to support advanced safety-oriented features, such as those deployed in autonomous driving or medical image analysis. Providing high degrees of accuracy in object recognition comes with a high computational cost that requires the support of specific hardware accelerators.

These accelerators are rarely designed to protect CNN parameters during the inference process, which may lead to object misclassification provoking unsafe situations. On the one hand, the multiplicity of bits that can be potentially flipped by single event upsets increases with larger technology scales. On the other hand, as CNNs interconnect to other systems, they become further exposed to malicious faults (attacks) that may crush their inference process by simply flipping a small number of vulnerable parameter bits.

In this talk, we will see how to exploit the assessment information provided by fault injection experiments to increase the robustness of a CNN against the occurrence of multiple bitflips by using error correction codes (ECCs). The approach will be exemplified using a floating point-based CNN that is prototyped on a programmable logic device. Then, we will study how the approach can be deployed without retraining the considered CNN, using well-known and proven ECCs and at an in-memory and zero-space cost.