# sonarqube-aem

This is a docker image that is identical to the official [sonarqube docker image](https://github.com/SonarSource/docker-sonarqube/blob/abaf14c38297974eb5de295d42e83066ddb84751/7.7-community/Dockerfile) with an added script to install [AEM-Rules-for-SonarQube](https://github.com/Cognifide/AEM-Rules-for-SonarQube) extension.

## Running

Latest from Docker Hub:

```sh
docker run --rm -p 9000:9000 ahmedmusallam/sonarqube-aem:latest
```

From Source:

Clone the repo and run the `build-and-run-container.sh` script. Or open it and run the commands manually. Sonar will run on port 9000.
