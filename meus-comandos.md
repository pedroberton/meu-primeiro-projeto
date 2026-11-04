# MEUS COMANDOS - Pedro - 100% LINUX + DOCKER

## LINUX - Dentro da pasta
1. ls = listar o que tem aqui
2. cd nome = entrar na pasta
3. nano arquivo = editar arquivo
4. mv velho novo = mover/renomear
5. cat arquivo = ver o que tem dentro

## DOCKER - Controlando containers
1. docker ps = ver o que tá ligado agora
2. docker ps -a = ver tudo, até desligado
3. docker logs nome = ver por que deu erro
4. docker rm -f nome = apagar na marra e liberar porta
5. docker build -t pedro-v3 . = FABRICAR minha imagem
6. docker run -d -p 8080:80 --name meu-v3 pedro-v3 = LIGAR minha imagem

## O QUE EU FIZ HOJE - 02/11/2026
1. Criei Dockerfile com FROM nginx e COPY index.html
2. Rodei docker build e deu Successfully built
3. Subi com docker run e vi no localhost:8080
Sou o Pedro - v3 com DOCKERFILE!

## QUANDO DER ERRO
1. Porta ocupada? -> docker ps, depois docker rm -f nome
2. Dockerfile minúsculo? -> mv dockerfile Dockerfile
3. Esqueci comando? -> docker --help ou Google, todo mundo usa cola
## GITHUB - Salvar na nuvem - 02/11/2026
1. gh auth login = logar no GitHub (fiz hoje e deu Logged in as pedroberton)
2. git status = ver o que tá vermelho (não salvo)
3. git add . = colocar tudo na caixinha
4. git commit -m "mensagem" = fechar a caixinha com nome
5. git push = mandar pro GitHub (hoje fiz git push -u origin main e subiu!)
6. git pull = puxar o que tá no GitHub pra meu PC

## MEU FLUXO TODO DIA
1. docker start meu-v3 (se já tenho container)
2. mudo o index.html
3. git add .
4. git commit -m "o que eu fiz"
5. git push
6. atualizo github.com/pedroberton/meu-primeiro-projeto e vejo lá
