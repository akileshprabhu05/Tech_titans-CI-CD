![example workflow](https://github.com/DashrathMundkar/cicd-java-maven-project/actions/workflows/maven.yml/badge.svg) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=purple) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) 

# cicd-java-maven-project
This is very basic/simple java-maven project for cicd environment and the purpose of the project is to showcase how to ship application from development to kubernetes environment using CICD.

## Build and deploy locally using docker

1. ```mvn clean install```


3. ```docker build -t hello-world .```


4. ```docker run -d -p 8080:8080 --name hello-world hello-world```


5. Access the application on ```localhost:8080```

