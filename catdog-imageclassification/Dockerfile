FROM tensorflow/tensorflow:1.8.0

ADD app /app

RUN pip install -r /app/requirements.txt

# Expose the port
EXPOSE 80

# Set the working directory
WORKDIR /app

# Run the flask server for the endpoints
CMD python app.py
