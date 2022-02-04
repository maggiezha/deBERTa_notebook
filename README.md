# deBERTa_notebook

You can run the deBERTa notebook using Colab directly, 

or on your local machine or server remotely by starting a PyTorch container following the below steps:

docker run -it --rm --gpus all -p 8888:8888 -v $PWD:/workspace/deberta nvcr.io/nvidia/pytorch:21.12-py3

cd /workspace/deberta 

Run the notebook:

cd /workspace/deberta 

jupyter notebook --port 8888

Then open the notebook in your browser(using the token)
