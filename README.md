[![build](https://github.com/agriii927/github-actions-for-java-demoapp/actions/workflows/ci.yml/badge.svg)](https://github.com/agriii927/github-actions-for-java-demoapp/actions/workflows/ci.yml)
##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
