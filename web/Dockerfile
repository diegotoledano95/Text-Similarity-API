FROM  python:3
WORKDIR /usr/src/app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . . 
RUN pip install ./en_core_web_md-3.4.1.tar.gz
CMD ["python","app.py"]