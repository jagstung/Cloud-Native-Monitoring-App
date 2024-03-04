Step 1:
Local Deployment with Flask:
Cloned the code repository.
Installed dependencies (psutil, Flask, Plotly, boto3) using pip.
Ran the Flask application locally using python3 app.py.

Step 2:
Dockerizing the Flask Application:
Created a Dockerfile specifying dependencies and application setup.
Built a Docker image using docker build.
Ran a Docker container locally using docker run.

Step 3:
Pushing Docker Image to ECR:
Created an Amazon ECR repository using boto3 in Python.
Pushed the Docker image to the ECR repository using docker push.

Step 4:
Kubernetes Deployment:
Created an EKS cluster and added a node group.
Defined a Kubernetes deployment and service using Python's kubernetes library.
Ran the Python script (eks.py) to deploy the application on the EKS cluster.
Checked deployment, service, and pod statuses using kubectl commands.
Accessed the application locally by forwarding the Kubernetes service port.
