# llama2_sentiment_analysis_stock_price_prediction

### What is quantization?

- In deep learning, models typically use 32-bit floating-point numbers (FP32) to represent weights and activations. However, this high precision comes at a cost: large memory requirements and slower inference times. Quantization reduces the precision of these numbers, using fewer bits to represent them. This can lead to:

- Memory savings: Lower-precision data types require less memory, making it possible to deploy models on devices with limited memory.
- Faster inference: Lower-precision arithmetic operations are generally faster than their higher-precision counterparts.
Improved energy efficiency: Reduced precision can lead to lower power consumption, making it suitable for edge devices or mobile applications.
