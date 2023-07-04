# Python image as the base image
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy requirements.txt to the working directory
COPY requirements.txt ./

# Install project dependancies 
RUN pip install --no-cache-dir -r requirements.txt

# Copy the entire project directory into the container
COPY . .

# Expose the port on which the web server will listen
EXPOSE 8080

# Define the command to start the web server
CMD ["python", "app.py"]