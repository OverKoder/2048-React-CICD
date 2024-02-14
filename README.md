# Getting Started with 2048

Fork and recreation of the 2048 Game with React and creating a CI/CD Pipeline for further deployment on Kubernetes

# CI /CD Pipeline
1.- Pull code from GitHub.\
2.- Scan for vulnerabilities with SonarQube (add a SonarQube webhook to continue the Pipeline when finishing).\
3.- Install dependecies with npm and OWASP.\
4.- Check file integrity with TRIVY.\
5.- Push the image to Docker Hub.\
6.- Deploy to container.\
7.- Deploy to K8s with deployment.yaml.

# K8s cluster
1.- Create two more AWS EC2 instances (one Master and one Slave).\
2.- In the Master Node create a pod cluster.\
3.- Join the Slave node to the Master cluster.
