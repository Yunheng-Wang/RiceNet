# hash:sha256:1d42e9f6cbb3c41698847bbbd3e923c49d2b8a3d6392e9e7b0f52f3964faab20
FROM registry.codeocean.com/codeocean/miniconda3:4.9.2-cuda11.7.0-cudnn8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        jupyter==1.0.0 \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    matplotlib==3.7.2 \
    scikit-learn==1.3.0 \
    scipy==1.10.1 \
    seaborn==0.12.2 \
    tensorflow==2.9.1
