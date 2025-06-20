# Estudos-Alura-Semana3-Task1

Na raiz do projeto foram adicionados os arquivos: Dockerfile, index.js, package.json

Para o build do container:

docker build -t minha-app .

Para rodar o container na porta 3000 e acessar via localhost:3000

docker run -p 3000:3000 minha-app
