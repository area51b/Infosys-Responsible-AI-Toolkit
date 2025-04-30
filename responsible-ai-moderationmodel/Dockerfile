FROM python:3.11.12
 
ENV DEBIAN_FRONTEND=noninteractive

# Copy entire project
COPY . /app

WORKDIR /app
RUN pip3 install -r requirements/requirement.txt

WORKDIR /app/src
CMD ["python3", "main.py"]
