## Fine-tuning and Deploy Microsft Phi-2 (HuggingFace Version) on SageMaker

Phi-2 is a Transformer with 2.7 billion parameters. It was trained using the same data sources as Phi-1.5, augmented with a new data source that consists of various NLP synthetic texts and filtered websites (for safety and educational value). When assessed against benchmarks testing common sense, language understanding, and logical reasoning, Phi-2 showcased a nearly state-of-the-art performance among models with less than 13 billion parameters. For more details, please refer to the [model card](https://huggingface.co/microsoft/phi-2) on Huggingface.

This is a sample project showing how to fine-tune and deploy the Phi-2 model on SageMaker. Here we are fine-tuning the Phi-2 model using summarization samples from the Dolly dataset from Huggingface Hub. The goal is to improve the model's overall summarization capability.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

