# Gemma_arabicQuotes
This repository contains code for fine-tuning the Gemma model on a dataset of Arabic quotes. The Gemma model is an open-source language model developed by Google.
# installation
To run the code in this repository, you will need to install the required dependencies. You can install them using pip:
`!pip install -q -U bitsandbytes==0.42.0
!pip install -q -U peft==0.8.2
!pip install -q -U trl==0.7.10
!pip install -q -U accelerate==0.27.1
!pip install -q -U datasets==2.17.0
!pip install -q -U transformers==4.38.0`
# Usage
1. Clone this repository to your local machine.
2. Open the provided Google Colab notebook.
3. Follow the instructions within the notebook to execute the code.
# Dataset
The dataset used for fine-tuning consists of Arabic quotes. It is sourced from the HeshamHaroon Arabic Quotes dataset.

# Fine-Tuning Process
1. Load the Gemma model and tokenizer.
2. Prepare the dataset for fine-tuning.
3. Define a formatting function for the training data.
4. Configure the Lora (Low-Rank adaptation) model for fine-tuning.
5. Train the Gemma model using Supervised Finetuning (SFTTrainer).
6. Generate text based on provided prompts after fine-tuning.

# Examples
Sample code snippets are provided in the notebook to demonstrate text generation using the fine-tuned Gemma model.
# Contributing
Contributions to this project are welcome. Please open an issue or pull request if you would like to contribute.


