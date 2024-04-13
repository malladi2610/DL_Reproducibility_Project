## This repository is about our reproducibility work on the research paper "Improved Baselines with Visual Instruction Tuning"

Link to the paper - [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/pdf/2310.03744.pdf)
Link to the Github repo - [LlaVA](https://github.com/haotian-liu/LLaVA)
Link to the blog post -

### Hardware configuration used
- GPUs -> 2 x A6000 Nvidia (48 GB)
- Operating system -> Ubuntu 22.04


### Proceduce to reproduce this paper
The paper can be reproduced by following a two step training process

1. Pretrain - Following the details in this link -> [Pretrain](https://github.com/haotian-liu/LLaVA?tab=readme-ov-file#pretrain-feature-alignment)
2. Finetune - Following the details in this link -> [Finetune](https://github.com/haotian-liu/LLaVA?tab=readme-ov-file#visual-instruction-tuning)
3. Inference - Following the details in this link -> [Inference](https://github.com/haotian-liu/LLaVA?tab=readme-ov-file#cli-inference)

To reproduce the ablation study

1. Download the gemma weights from the hugging face -> [Gemma Checkpoints](https://huggingface.co/google/gemma-2b/tree/main)
2. Follow the Pretrain and the Finetune steps as above
3. Run the inference as above



The scripts we used along with the other models can be found in the following folder **reproducibility_project**


## Training Report
https://api.wandb.ai/links/darrynbiervliet/lvsbf5ax
