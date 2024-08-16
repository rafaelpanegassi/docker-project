# docker-project

#### 1 - Clone o projeto para seu ambiente local.

1.1 - Clone do repositório:
```bash
git clone https://github.com/rafaelpanegassi/docker-project.git
```
1.2 - Entre na pasta:
 ```bash
 cd docker-project
 ```

#### 2 - Build a imagem e rode o container 

2.1 - Build a imagem criada do Dockerfile:
```bash
docker build -t my-first-image .
```
2.2 - Suba o container da imagem que foi criada:
```bash
docker run -d -p 8501:8501 --name my-first-container my-first-image
```

#### 3 - Acesse a aplicação

3.1 - Digite o seguinte no seu navegador:
```bash
localhost:8501
```

