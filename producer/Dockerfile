FROM python:3.9-slim

# Set environment variable
ENV PYTHONPATH=/usr/src/app

# Set working directory
WORKDIR /app

# Copy files into the container
COPY producer.py /app/
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Define default entrypoint
CMD ["python", "producer.py"]
