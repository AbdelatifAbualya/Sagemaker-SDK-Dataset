# AWS SageMaker SDK Assistant Fine-Tuning Dataset

This repository contains a dataset specifically created to fine-tune Large Language Models (LLMs) to act as assistants for AWS SageMaker SDK usage.

## Dataset Composition

The dataset is structured in JSONL format and consists of three main components:

1. **Apache 2.0 Licensed Examples (10%-15%)**
   - Derived directly from the [Amazon SageMaker Examples GitHub repository](https://github.com/aws/amazon-sagemaker-examples), which is distributed under the Apache 2.0 license.

2. **Semi-Synthetic Data**
   - Approximately 10% of the dataset.
   - Created by modifying original AWS examples with slight variations in inputs and outputs to enhance model generalization.

3. **Synthetic Data (DeepSeek v3)**
   - About 75%-80% of the dataset.
   - Fully synthetic entries generated using DeepSeek v3, hosted on Fireworks.ai, leveraging custom Python scripts to target specific AWS SageMaker functionalities and scenarios.

## Data Quality Assurance
- Each synthetic and semi-synthetic entry was generated and then subjected to random manual reviews by the dataset creator to ensure accuracy and relevance.

## Licensing Information
- Original AWS SageMaker examples are covered under the Apache 2.0 license.
- Semi-synthetic and fully synthetic data are original works created specifically for this dataset and are distributed under the MIT license.

## Intended Use
This dataset is primarily intended for:
- Fine-tuning LLMs to assist users with AWS SageMaker SDK operations.
- Training assistants or chatbots specialized in AWS SageMaker functionalities.

## Contribution and Feedback
Contributions, suggestions, and feedback are welcome. Please open an issue or pull request to contribute enhancements or corrections.

