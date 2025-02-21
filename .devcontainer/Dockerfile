# Use the official Python base image
FROM mcr.microsoft.com/devcontainers/python:latest

# Set the working directory
WORKDIR /workspace

# Copy the requirements.txt file
COPY requirements.txt .

# Install dependencies during the build
RUN pip install --no-cache-dir -r requirements.txt
