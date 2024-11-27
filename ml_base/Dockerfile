FROM pytorch/pytorch:2.5.1-cuda12.4-cudnn9-runtime
LABEL maintainer="Ruiqi Chen" version="1.0" description="Pytorch, NeurODE, and visualization tools w/o Jupyter"
RUN pip install --no-cache-dir scipy scikit-learn torchdiffeq
RUN pip install --no-cache-dir matplotlib pandas seaborn