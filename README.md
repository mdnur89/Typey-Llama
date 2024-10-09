# Web Typey-Llama

Private LLM chatbot supporting Llama 3, Mistral and other open source models.

- Fully private = No conversation data ever leaves your computer
- Runs in the browser = No server needed and no install needed!
- Works offline
- Easy-to-use interface on par with ChatGPT, but for open source LLMs

The inference engine provided by [webllm](https://github.com/mlc-ai/web-llm).

WebGPU support is required, various models might have specific RAM requirements.

To compile code, run

```
yarn
yarn build-and-preview
```

If you're looking to make changes, run the development environment with live reload:

```
yarn
yarn dev
```

## Supported models

TinyLlama-1.1B-Chat-v0.4-q4f32_1-1k - 600MB  
Llama-3-8B-Instruct-q4f16_1 - 4.3GB  
Phi1.5-q4f16_1-1k - 1.2GB  
Mistral-7B-Instruct-v0.2-q4f16_1 - 4GB
