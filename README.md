# Jenkins Pipeline for Java based application using Maven, SonarQube, Argo CD, Helm and Kubernetes

## Prerequisites:

  Java application code hosted on a Git repository 

  Jenkins server

  Kubernetes Cluster

  Install Kubectl

  Install docker

  SonarQube

  Argo CD

## Configure a Sonar Server locally


  apt install unzip

  adduser sonarqube

  wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.4.0.54424.zip

  unzip *

  chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424
  
  chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424
  
  cd sonarqube-9.4.0.54424/bin/linux-x86-64/
  
  ./sonar.sh start


### Follow the article for doing this project : [Click here](https://anjumohan.hashnode.dev/jenkins-pipeline-for-java-based-application-using-maven-sonarqube-argo-cd-and-kubernetes)
