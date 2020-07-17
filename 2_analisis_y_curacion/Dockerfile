FROM jupyter/base-notebook 

RUN mkdir src/
WORKDIR src/
COPY . .

RUN pip3 install -r requirements.txt
RUN pip3 install jupyterlab

RUN python3 module.py

WORKDIR notebooks/

CMD ["jupyter", "lab", "--port=8888", "--no-browser", "--ip=0.0.0.0", "--allow-root"]