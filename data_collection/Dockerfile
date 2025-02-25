# Use official Python image
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy requirements and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the script and environment file
COPY collect_data.ipynb .
COPY data_preprocessing.ipynb .

# Run the script on container startup
CMD ["python", "collect_data.py"]
