## Fine-tuning Meta-Llama-3 1.8B Instruct with LoRA  

## Introduction  
This project fine-tunes the Meta-Llama-3 1.8B Instruct model using LoRA.  

## Downloading the Model  
You can download the fine-tuned model through the following methods:  
- **Transformers Library**: You can directly use Hugging Face's Transformers library to download the model.
- https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct
- **Modelscope**: Alternatively, you can download the model via Modelscope.  

The repository includes the Adapter files that have been fine-tuned with LoRA, which you can use as needed.  

## Dataset  
The dataset used in this project is [LooksJuicy/Chinese-Roleplay-SingleTurn](https://huggingface.co/datasets/LooksJuicy/Chinese-Roleplay-SingleTurn). Similarly, you can download this dataset from Hugging Face for fine-tuning.  

## GPU  
An RTX 4090 was used for training for 3 hours.
