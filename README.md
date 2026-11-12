# Meu Primeiro Projeto - Docker + Nginx

Meu primeiro site rodando em container Docker.

## O que eu aprendi
- Linux: pwd, ls, cd, chmod, scripts .sh
- Docker: build, run, ps, stop, rm, volume com -v
- Volume: mudar o index.html sem precisar dar build de novo

## Como rodar

docker run -d --name meu-v5 -p 8081:80 -v $(pwd):/usr/share/nginx/html nginx

Depois abre no navegador: http://localhost:8081

## Tecnologias
- Docker
- Nginx
- Linux
