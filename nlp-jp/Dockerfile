FROM ototadana/nlp-jp
MAINTAINER yosuke.yasuda.919@gmail.com

RUN conda install -y jupyter

RUN pip install git+https://github.com/nikitakit/xdbg

CMD jupyter notebook --NotebookApp.token='' --ip 0.0.0.0 --port 11111 --allow-root --config=/home/shared/jupyter_notebook_config.json --notebook-dir=/home
