# Fine-tuning Generative Models with Reinforcement Learning: Best-of-N Distillation

This project focuses on fine-tuning generative models using reinforcement learning techniques. Specifically, it employs the Best-of-N distillation method to optimize generative outputs.

## Authors

- **Timofey Efimov**
- **Tong Yang**

## Instructions

### 1. Classifier guidance

Follow the instructions from guided diffusion repository, can also vary the parameters which we mentioned in the paper to have higher guidance scale or change number of sampling steps by changing the configs accordingly

### 2. LLM alignment experiments

Change the google drive into which you want to mount the notebook if you wish inside Google Colab, and run the code in the Google Colab

### 3. Diffusion zero-shot posterior sampling 

Simply run the code in the google colab with turned on GPU support ( experiments were conducted on A100 )