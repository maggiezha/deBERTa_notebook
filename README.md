# deBERTa_notebook

You can run the deBERTa notebook "DeBERTa for Question Answering Colab" using Colab directly, 

or run the deBERTa notebook "DeBERTa for Question Answering" on your own machine following the below steps:

1. Download the notebook to your own machine, go to the directory having the notebook.

2. Start a NGC PyTorch container:

$ docker run -it --rm --gpus all -p 8888:8888 -v $PWD:/workspace/deberta nvcr.io/nvidia/pytorch:21.12-py3

3. Run the notebook:

$ cd /workspace/deberta 

$ jupyter notebook --port 8888

Then open the notebook in your browser(using the token), and play with the notebook.

Please notice the finetuning step could take many hours, it can run on multiple GPUs.

You can change the batch size based on your GPU memory size, and increase the number of epochs to get a better finetuning result.
