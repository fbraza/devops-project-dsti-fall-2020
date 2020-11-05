# DevOps assignment



## Tasks fulfilled

- [ ]  **Create a web application**

  - [x] Complete code
  - [ ] Complete all tests (missed one)

- [x] **Apply CI/CD pipeline**

  - [x] Travis CI with testing
  - [x] Deployment on Heroku

- [ ] **Configure and provision a virtual environment and run your application using IaC approach**

  - [x] Configure with Vagrant, 1 VM with centOS v7
  - [ ] Provision the VM with Ansible for:
    - [x] Language runtime
    - [x] Database
    - [x] Git (ssh forwarding for private repository)
    - [x] My application
    - [ ] Health-check

- [x] **Build Docker image of your application**

  - [x] Create Docker image
  - [x] Push the image (https://hub.docker.com/repository/docker/fbraza/webapp-v1)
  - [x] Ignore unnecessary files (`COMPOSE_DOCKER_CLI_BUILD=1 docker-compose build`)

- [x] **Make container orchestration using Docker Compose**

  - [x] Create a `docker-compose.yml` file with that will start your application
  - [x] Right ENV variables (*Sergei pull request*)
  - [x] Attach volume to save database data

- [ ] **Make docker orchestration using Kubernetes**

  - [x] Install Kubernetes cluster using Minikube
  - [x] Create Kubernetes deployment YAML file (test curl with minikube ssh)

`kubectl exec full-app-5c669d49dd-hnxcd -- printenv` >> env variables 

`kubectl get pods faouzi-webapp-55976475f9-94jv8 -o jsonpath='{.spec.containers[*].name}'`

- [ ] Create Kubernetes service YAML files

- [ ] Create Kubernetes persistent volume and persistent volume claim YAML files

- [ ] **Make a service mesh using Istio**

- [ ] **Describe your project in the `README.md` file**

  

