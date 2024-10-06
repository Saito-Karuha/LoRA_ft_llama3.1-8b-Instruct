# 使用 LoRA 微调 Meta-Llama-3 1.8B Instruct  

## 简介  
本项目使用 LoRA 对 Meta-Llama-3 1.8B Instruct 模型进行微调。  

## 下载模型  
您可以通过以下方式下载微调后的模型：  
- **Transformers 库**: 您可以直接使用 Hugging Face 的 Transformers 库来下载该模型。  
- **Modelscope**: 另外，您也可以通过 Modelscope 下载模型。  

仓库中包含了经过 LoRA 微调后的 Adapter 文件，您可以根据需要进行使用。  

## 数据集  
本项目使用的数据集为 [LooksJuicy/Chinese-Roleplay-SingleTurn](https://huggingface.co/datasets/LooksJuicy/Chinese-Roleplay-SingleTurn)。同样，您可以从 Hugging Face 下载该数据集以进行微调。  

## GPU
使用了一块RTX 4090训练了3小时
