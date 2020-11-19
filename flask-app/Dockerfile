#Use Python Image
FROM python:3.5
RUN apt-get update && apt-get install -y python3-pip
COPY . .
RUN pip3 install flask flask-sqlalchemy PyMySQL cryptography
EXPOSE 5000
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]
# Install apt dependencies
 
# Copy contents into image
 
# run pip dependencies
 
# Expose correct port

# Create an entrypoint

