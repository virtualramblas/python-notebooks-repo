# Semantic search on unseen images with OpenAI's CLIP
A Jupyter notebook to do semantic search on unseen and unlabelled images using [OpenAI's CLIP](https://openai.com/blog/clip/).  
This notebook has been created after reading the related [paper](https://cdn.openai.com/papers/Learning_Transferable_Visual_Models_From_Natural_Language_Supervision.pdf) and it has been partially derived from the following [Colab example](https://github.com/openai/CLIP/blob/main/notebooks/Interacting_with_CLIP.ipynb), but to be used on a local Jupyter Notebook server.  
  
#### Setup
- Create a virtual environment.
- Install Jupyter for it.
- Import the dependencies listed in the associated requirements file.
- Download the pre-trained CLIP model from [here](https://openaipublic.azureedge.net/clip/models/40d365715913c9da98579312b702a82c18be219cc2a73407c4526f58eba950af/ViT-B-32.pt).
- Download an OpenAI case insensitive tokenizer from [here](https://openaipublic.azureedge.net/clip/bpe_simple_vocab_16e6.txt.gz) (don't extract the archive content).
- Run Jupyter.
  
It has been tested on Windows machines with an NVIDIA GPU. GPU is **required** in order to execute the code in this notebook.  
  
#### Usage
Follow the description for each cell of the notebook.
  
