# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into /app in the container
COPY . /app

# Install packages defined in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make this port available outside the container
EXPOSE 5000

# Define the environment variable
ENV FLASK_APP=app.py

# Run the app.py when container launches
CMD ["python", "app.py"]