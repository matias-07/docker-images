FROM ubuntu

RUN apt update && apt install -y python3 python3-pip openjdk-8-jdk

RUN pip install pyspark jupyterlab

WORKDIR /root/workspace

EXPOSE 8888

CMD ["jupyter-lab", "--allow-root", "--no-browser", "--ip", "0.0.0.0"]
