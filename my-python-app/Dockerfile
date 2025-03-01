# Use official Python image
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy app files to container
COPY requirements.txt requirements.txt
COPY app.py app.py

# Install dependencies
RUN pip install -r requirements.txt

# Expose the Flask port
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]
