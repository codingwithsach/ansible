FROM python:3.12.3-slim

WORKDIR /app

RUN pip install ansible

COPY requirements.txt /app

RUN pip install --no-cache-dir -r requirements.txt

CMD ["ansible-playbook", "playbook.yml"]