# FLASK APP

**1. Build the image**

    `docker build -t flask-app:latest .`

**2. Run the container**

    Run the container in deattched mode and expose port 5000

    `docker run -d -p 5000:5000 --name flask-app flask-app:latest`