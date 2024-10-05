# Use official python Docker image
FROM python:3.9-slim

# Set the working directory in container
WORKDIR /app

# copy current dir under /app in container
COPY . /app

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 for Flask app
EXPOSE 5000

# Run the flask app
CMD ["python", "app.py"]