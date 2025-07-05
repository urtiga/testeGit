# testeGit
Olá esse projeto é apenas um teste que estou utilizando para memorizar conhecimentos em como criar um projeto da forma correta através das seguintes tecnologias: Git, GitHub, HTML , CSS, JS, TS.

abaixo um passo a passo do que fiz até agora
1- criar um repositório no GitHub com o nome da sua preferencia
2- em seguida copiar o HTTPS
3- vá no git bash, e utilize o comando git clone https.urldorepositorio
4- agora, utilize o coamndo cd nomeRepositorio para entrar na pasta do arquivo
5- de atalho utilize code . para abrir o vs já na pasta que vamos utilizar.
6- já no vs, crie um arquivo index.html, style.css e index.ts
7-em seguida crie uma pasta code e mova o css e o ts para a mesma
8-ao concluir essa etapa utilize no terminal do vs, tsc --init para invocar o tsconfig.json.
9- dentro do tsconfig.json, descomente rootDir e adcione após a / o nome da nossa pasta (code). utilize cntrl + f para facilitar a busca
10- desconmente outDir e após o / coloque prod.
11- desconmente noImplicityAny
12- desconmente noEmitOnError
13- agora utilize o comando tsc, e assim será criado um index.js já dentro daa pasta prod
14- git add *
15- git status
16- git add *
17- git status 
18- git commit -a -m "mensagem do commit"
19- git status
20- git push
21 - git log (pra conferir)