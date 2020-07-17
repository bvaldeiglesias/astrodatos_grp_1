FROM jupyter/base-notebook 

WORKDIR .
COPY . .

RUN pip3 install -r requirements.txt
RUN pip3 install jupyterlab

RUN python3 module.py

# RUN rm /src/data/raw_data.csv


CMD ["jupyter", "lab", "--port=8888", "--no-browser", "--ip=0.0.0.0", "--allow-root"]