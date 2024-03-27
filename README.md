# Fine-Tune and Deploy Microsoft Phi-2 (Hugging Face Version) on SageMaker

Phi-2 is a transformer model with 2.7 billion parameters, trained on a dataset that includes data from Phi-1.5 as well as additional synthetic texts and filtered websites for safety and educational purposes. When evaluated against benchmarks for common sense, language understanding, and logical reasoning, Phi-2 demonstrated nearly state-of-the-art performance among models with fewer than 13 billion parameters. For more details, refer to the [model card](https://huggingface.co/microsoft/phi-2) on Hugging Face.

## Overview

This project demonstrates how to fine-tune and deploy the Phi-2 model on SageMaker. We fine-tune Phi-2 using samples from the [Dolly dataset](https://huggingface.co/datasets/databricks/databricks-dolly-15k) for summarization, aiming to enhance the model's summarization capabilities.

## Getting Started

1. Open a JupyterLab notebook within the Amazon Sagemaker Studio.
2. Clone this repository.
4. Open and follow the instructions in the `train-evaluate-llms-2024-trl-phi2.ipynb` notebook to fine-tune the Phi-2 model with QLoRA (Efficient Fine-tuning of Quantized LLMs).

## Deployment

After fine-tuning, the notebook guides you through deploying the tuned model as a SageMaker endpoint. You will also deploy the base Phi-2 model as a SageMaker endpoint to compare the original model with the fine-tuned version.

## Security

For security-related issues, please refer to [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications).

## License

This library is licensed under the MIT-0 License. See the LICENSE file for more details.
