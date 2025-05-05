# Finetuning LLama-3.2-3B for Q&A using [unsloth](https://unsloth.ai)

Original notebook [here](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Meta_Synthetic_Data_Llama3_2_(3B).ipynb#scrollTo=FqfebeAdT073)


- Uses [Meta-llama synthethic-data-kit](https://github.com/meta-llama/synthetic-data-kit) to generate question and answer pairs fully locally which will be used for finetuning Llama 3.2 3B!
- Fine-tuning Synthetic Dataset with Unsloth
- LoRA adapters so we only need to update 1 to 10% of all parameters
- Saving to float16 for VLLM
- GGUF / llama.cpp Conversion


