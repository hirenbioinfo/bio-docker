FROM conda/miniconda3

RUN conda update --all -y &&\
    conda config --add channels conda-forge &&\
    conda config --add channels bioconda &&\
    conda config --set show_channel_urls yes &&\
    conda install -c "bioconda/label/cf201901" filtlong

CMD ["/bin/bash"]
