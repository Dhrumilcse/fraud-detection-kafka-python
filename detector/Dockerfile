FROM python:3.6

WORKDIR /Users/dhrumil/Documents/Projects/kafka/fraud_detection

ADD ./requirements.txt ./
RUN pip install -r requirements.txt
ADD ./ ./

CMD ["python", "app.py"]