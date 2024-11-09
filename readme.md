# PetClinic CI/CD Application
Springboot and Thymeleaf based web application from this [repo](https://github.com/spring-projects/spring-petclinic)
Simplified for Kubernetes deployment 

### Steps to run
1. Clone this repository - ```git clone https://github.com/spring-lab-01/petclinic-cicd.git```
2. Turn on kubernetes cluster in local machine using https://docs.docker.com/desktop/features/kubernetes/#install-and-turn-on-kubernetes
3. cd to project location from terminal
4. run command - ```kubectl apply -f kube```
5. verify application - http://localhost:8080

## References
- https://docs.docker.com/guides/java/
- https://github.com/spring-projects/spring-petclinic

## License
The Spring PetClinic sample application is released under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).
