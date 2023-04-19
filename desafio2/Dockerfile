FROM python:3.10
WORKDIR /app
COPY requiriments.txt ./
RUN pip install --no-cache-dir -r requiriments.txt
EXPOSE 5000
COPY . .
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]