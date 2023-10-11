## Amazon SageMaker Llama 2 Inference via Response Streaming

Llama 2 is a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. The fine-tuned LLMs, called Llama-2-Chat, are optimized for dialogue use cases. Llama 2 outperforms other open source language models on many external benchmarks, including reasoning, coding, proficiency, and knowledge tests.



This repo covers Deploy and Inference Llama 2 Models on SageMaker via Response Streaming.

| DLC | Model ID | Deploy Notebook | Inference Notebook |
| --- | --- | --- | --- |
| HF TGI | meta-llama/Llama-2-7b-chat-hf | [Deploy](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-hf-tgi/llama-2-7b-chat-hf/1-deploy-llama-2-7b-chat-hf-tgi-sagemaker.ipynb) | [Inference](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-hf-tgi/llama-2-7b-chat-hf/2-sagemaker-realtime-inference-llama-2-7b-chat-hf-tgi-streaming-response.ipynb) |
| HF TGI | meta-llama/Llama-2-13b-chat-hf | [Deploy](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-hf-tgi/llama-2-13b-chat-hf/1-deploy-llama-2-13b-chat-hf-tgi-sagemaker.ipynb) | [Inference](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-hf-tgi/llama-2-13b-chat-hf/2-sagemaker-realtime-inference-llama-2-13b-chat-hf-tgi-streaming-response.ipynb) |
| LMI | meta-llama/Llama-2-7b-chat-hf | [Deploy](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-lmi/llama-2-7b-chat/1-deploy-llama-2-7b-lmi-response-streaming.ipynb) | [Inference](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-lmi/llama-2-7b-chat/2-inference-llama-2-7b-lmi-response-streaming.ipynb) |
| LMI | meta-llama/Llama-2-13b-chat-hf | [Deploy](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-lmi/llama-2-13b-chat/1-deploy-llama-2-13b-chat-lmi-response-streaming.ipynb) | [Inference](https://github.com/windson/amazon-sagemaker-llama2-response-streaming-recipes/blob/main/llama-2-lmi/llama-2-13b-chat/2-inference-llama-2-13b-chat-lmi-response-streaming.ipynb) |

[Sagemaker Real-time Inference now supports response streaming](https://aws.amazon.com/about-aws/whats-new/2023/09/sagemaker-real-time-inference-response-streaming)


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

