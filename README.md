# Khomichenko ukma node + docker server

## Run Locally

Clone the project

```bash
  git clone https://github.com/X0lotl/ukma_docker.git
```

Go to the project directory

```bash
  cd ukma_docker
```

Build docker image

```bash
  docker build . -t ukma/docker-server
```

Run docker image with memory and cpu limit

```bash
  sudo docker run -m 512m --cpus=2 -p 80:8080 -d ukma/docker-server
```

