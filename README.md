# Domain Expert Language Model

This repository contains a demonstration of the fine-tuning process for the Meta Llama2 7B model. The project includes model evaluation before and after fine-tuning, as well as screenshots of responses with Healthcare-specific data.

## Overview

The repository showcases:
- Model evaluation before fine-tuning.
- Fine-tuning process on a Healthcare-specific dataset.
- Screenshots of model responses before and after fine-tuning.

## Getting Started with SageMaker

To use AWS SageMaker, follow these steps:

1. **Create an AWS Account**
   Ensure you have an AWS account. 

2. **Open SageMaker**
   - Navigate to the [AWS Management Console](https://aws.amazon.com/console/).
   - Go to the Amazon SageMaker service.

3. **Setup Notebook Instance**
   - Create a new notebook instance or use an existing one.
   - Open the notebook instance and create a new notebook.

4. **Run the Code**
   - Copy and paste the code from the repository into the notebook, or upload the `.ipynb` files.
   - Run the code to execute and view the results.

   Make sure you have the necessary permissions and resources set up in your AWS account.

## Model Evaluation

Before fine-tuning, the Llama2 model was evaluated to assess its performance on the given task. The evaluation results are documented in the `Model_evaluation.ipynb` notebook.

## Fine-Tuning

The fine-tuning process involved training the Llama2 model on an Healthcare-specific dataset to enhance its performance. Details of the fine-tuning process can be found in the `Model_fineTuning.ipynb` notebook.

To illustrate the impact of fine-tuning, screenshots of the model’s responses before and after the process are provided.

## Files and Directories

- `Model_evaluation.ipynb` - Notebook with evaluation results.
- `Model_fineTuning.ipynb` - Notebook with fine-tuning details.
- `screenshots/` - Directory containing before and after screenshots of model responses.
