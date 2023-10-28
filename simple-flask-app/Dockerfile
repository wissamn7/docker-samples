# Use a Python base image
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy the application code into the image
COPY . /app

# Install application dependencies
RUN pip install -r requirements.txt

# Expose port 8080
EXPOSE 8080

# Specify the command to run the application
CMD ["python", "app.py"]
