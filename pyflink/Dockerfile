FROM python:3.8.13
RUN apt update
RUN apt install -y default-jre
RUN pip install apache-flink
RUN pip install jupyterlab
WORKDIR /root/workspace
EXPOSE 8888
ENTRYPOINT ["bash"]
