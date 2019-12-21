FROM python


EXPOSE 80
WORKDIR /app
ADD ./ /app

RUN pip install -r ./requirements.txt
CMD python main.py
