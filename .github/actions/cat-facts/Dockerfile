FROM python:3

COPY requirements.txt ./

RUN PIP install --no-cache-dir -r requirements.txt

COPY . . 

CMD ["python", "/src/main.py"]
