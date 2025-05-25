# 从0到1构建大模型
#该项目旨在深入理解大模型的原理。玩玩各种有意思的小项目
1. llms0-1.ipynb 记录了从0到1构建类似GPT模型的过程
2. finetune+inferenceGPT2.ipynb 记录了如何使用添加额外的分类头使得decoder-only架构的大模型来分类文本
3. fine-tuning-classification.ipynb 通过修改loss函数来微调decoder-only的生成式大模型，将生成式任务任务转化成二进制分类任务；
4. AutoencoderUnknownVul.ipynb 通过自编码来进行漏洞检测
