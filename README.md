# pyflask-docker
pyflask-docker Learning Repo.

Step1: Clone Repo. Modify if required.

Step2: Build Docker Image. `docker build -t dcnsakthi/pyflask-docker:latest .`

Step3: Push Docker Image to DockerHub. `docker push dcnsakthi/pyflask-docker:latest`

Step4: Pull Docker Image to Locally. `docker pull dcnsakthi/pyflask-docker:latest` Or Run Docker Container. `docker run -p 5000:5000 dcnsakthi/pyflask-docker:latest`

Step5: Browse through the URL. `http://localhost:5000/`
