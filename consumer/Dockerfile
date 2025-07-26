FROM python:3.9-slim

# Set environment variable
ENV PYTHONPATH=/usr/src/app

# Set working directory
WORKDIR /app

# Copy files into the container
COPY consumer.py /app/
COPY requirements.txt /app/

# Install dependencied
RUN pip install --no-cache-dir -r requirements.txt

# Define default entrypoint
CMD ["python", "consumer.py"]
