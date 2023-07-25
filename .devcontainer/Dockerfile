FROM python:3.11

WORKDIR /app/mkdocs
EXPOSE 8000

RUN apt-get update && apt-get install gnupg2 -y && python -m pip install --upgrade pip

COPY docs/requirements.txt docs/requirements.txt
RUN pip install -r docs/requirements.txt

COPY . .

CMD ["mkdocs", "serve", "--dev-addr=0.0.0.0:8000"]
