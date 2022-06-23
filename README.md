# pquad_public
[PQuAD](https://arxiv.org/abs/2202.06219) is a crowdsourced reading comprehension dataset on Persian Wikipedia articles. 
Since the implementation of this dataset hasn't been yet implemented in the hugging face, I have prepared the essential set ups in the [hugging face](https://huggingface.co/datasets/Shayanvsf/pquad_public) to enable using this data set using the load_dataset library :

**from datasets import load_dataset**

**dataset = load_dataset("Shayanvsf/pquad_public")**

By running the above command, the output will be a Dataset Dict that is compatible with the available Transformer models in hugging face.




