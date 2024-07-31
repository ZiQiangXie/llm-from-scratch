## 从头实现大模型
目前已经实现了llama3、qwen1.5、qwen2、chatglm3、glm4、deepseekv2、internlm2.5等多个国内外知名大模型。
<br>
* 增加 qwen2-0.5b，运行仅占用约1GB内存，对于个人pc比较友好，用于学习大模型的推理流程；
* 增加 qwen2 模型微调，以自我认知和医疗数据集对 instruct 对话模型进行微调，学习微调流程;
<br>
显存占用：7b 模型最低占用约 11.7GB，1.5b 模型约占用 4.9GB，0.5b 模型约占用 3.4GB；


## llama3-from-scratch.ipynb
original project, support weights that suffix with pth. 原始工程，支持llama3原始的pth格式的权重。
## llama3-from-scratch-hf.ipynb
> support weights that suffix with safetensors. 支持llama3的hf格式的权重，以safetensors为后缀。
## llama3-from-scratch-hf-kvcache.ipynb
> support hf weights and kvcache. 支持hf权重，并新增了kvcache，用于decoder的自回归解码。
## chatglm3-from-scratch.ipynb
> support hf weights and kvcache. 支持hf权重和kvcache，用于decoder的自回归解码。
## glm4-from-scratch.ipynb
> support hf weights and kvcache. 支持hf权重和kvcache，用于decoder的自回归解码。
## qwen1.5-from-scratch.ipynb
> support hf weights and kvcache. 支持hf权重和kvcache，用于decoder的自回归解码。
## qwen2-from-scratch.ipynb
> support hf weights and kvcache. 支持hf权重和kvcache，用于decoder的自回归解码。
## deepseekv2-from-scratch.ipynb
> support hf weights. 支持hf权重。
## internlm2_5-from-scratch.ipynb
> support hf weights and kvcache. 支持hf权重和kvcache，用于decoder的自回归解码。

<br>
<br>
<br>

## README-en.md
> 原工程README
## README-zh.md
> 原始工程README中文翻译版
## 参考：
https://github.com/naklecha/llama3-from-scratch