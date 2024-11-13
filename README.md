---
library_name: transformers.js
base_model: Qwen/Qwen2.5-Coder-3B-Instruct
---

https://huggingface.co/Qwen/Qwen2.5-Coder-3B-Instruct with ONNX weights to be compatible with Transformers.js.

Note: Having a separate repo for ONNX weights is intended to be a temporary solution until WebML gains more traction. If you would like to make your models web-ready, we recommend converting to ONNX using [🤗 Optimum](https://huggingface.co/docs/optimum/index) and structuring your repo like this one (with ONNX weights located in a subfolder named `onnx`).