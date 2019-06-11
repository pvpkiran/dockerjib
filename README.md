# Getting Started With JIB Plugin for creating images

### Reference Documentation
 https://github.com/GoogleContainerTools/jib  
 
### Instructions

_mvn clean compile jib:build_  =====> This will build and push the image to docker(url specified in pom. Check reference documentation for providing credentials)  

_docker run -d -p 8090:8090 --name testingjib pvpkiran/testingjib_   ===> To pull and run locally.

### Testing
http://localhost:8090/hello

