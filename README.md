# Quantization

Quantization is a technique used in deep learning to reduce the precision of the numbers representing a model’s weights and activations, typically from 32-bit floating point (FP32) to 8-bit integers (INT8). This reduces the model's size and computational requirements, allowing for faster inference and lower memory usage, particularly on edge devices like smartphones and embedded systems.

Quantization can be done in two primary ways:

- Post-training quantization: Applied after the model is trained, where weights and activations are quantized.
- Quantization-aware training (QAT): The model is trained with quantization effects simulated, leading to better accuracy after quantization, compared to post-training quantization.

It’s commonly used to deploy deep learning models in resource-constrained environments without sacrificing much accuracy.
