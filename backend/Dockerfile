FROM python:3.10-bullseye
EXPOSE 5000
RUN pip install --upgrade pip
WORKDIR ./
RUN pip install rembg
RUN wget -P /root/.u2net/ https://github.com/danielgatis/rembg/releases/download/v0.0.0/u2net.onnx
CMD rembg s