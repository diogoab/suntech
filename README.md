# Test Suntech

1 - Instalar dependencias
```
npm install express
```

2 - Build da Imagem 
```
docker build -t diogo-node-hello-app
```

3 - Criar container
```
docker run -d -p 3000:3000 diogo-node-hello-app
```
