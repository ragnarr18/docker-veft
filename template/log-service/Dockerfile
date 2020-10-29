FROM python:3.7

WORKDIR /usr/src/app
ENV PYTHON_ENV production

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "./app.py" ]