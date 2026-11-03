# MEUS COMANDOS - Pedro - 100% LINUX + DOCKER

## LINUX - Dentro da pasta
ls = listar o que tem aqui
cd nome = entrar na pasta
nano arquivo = editar arquivo
mv velho novo = mover/renomear
cat arquivo = ver o que tem dentro

## DOCKER - Controlando containers
docker ps = ver o que tá ligado agora
docker ps -a = ver tudo, até desligado
docker logs nome = ver por que deu erro
docker rm -f nome = apagar na marra e liberar porta
docker build -t pedro-v3 . = FABRICAR minha imagem
docker run -d -p 8080:80 --name meu-v3 pedro-v3 = LIGAR minha imagem

## O QUE EU FIZ HOJE - 02/11/2026
1. Criei Dockerfile com FROM nginx e COPY index.html
2. Rodei docker build e deu Successfully built
3. Subi com docker run e vi no localhost:8080
Sou o Pedro - v3 com DOCKERFILE!

## QUANDO DER ERRO
Porta ocupada? -> docker ps, depois docker rm -f nome
Dockerfile minúsculo? -> mv dockerfile Dockerfile
Esqueci comando? -> docker --help ou Google, todo mundo usa col
a
## GITHUB - Salvar na nuvem - 02/11/2026
gh auth login = logar no GitHub (fiz hoje e deu Logged in as pedroberton)
git status = ver o que tá vermelho (não salvo)
git add . = colocar tudo na caixinha
git commit -m "mensagem" = fechar a caixinha com nome
git push = mandar pro GitHub (hoje fiz git push -u origin main e subiu!)
git pull = puxar o que tá no GitHub pra meu PC

## MEU FLUXO TODO DIA
1. docker start meu-v3 (se já tenho container)
2. mudo o index.html
3. git add .
4. git commit -m "o que eu fiz"
5. git push
6. atualizo github.com/pedroberton/meu-primeiro-projeto e vejo lá
