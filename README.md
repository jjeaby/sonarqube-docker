# sonarqube-docker
## sonarqube docker compose file 
#### sonarqube compose up command
```
$ docker-compose up -d                                                           
```

#### sonarqube scanner run command
```
$ sonar-scanner \
-Dsonar.projectKey=[sonarqube scan project name] \
-Dsonar.sources=[sonarqube scan source directory] \
-Dsonar.host.url=http://127.0.0.1:39270 \
-Dsonar.login=[sonarqube user token]
```

