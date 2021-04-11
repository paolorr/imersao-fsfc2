# Imersão Fullcycle 2 - Codelivery
![Imersão Full Stack && Full Cycle](https://events-fullcycle.s3.amazonaws.com/events-fullcycle/static/site/img/grupo_4417.png)

Participe gratuitamente: https://imersao.fullcycle.com.br/

## Sobre o repositório
Esse repositório contém todo código utilizado durante as aulas para referência.

Faça seu fork e também nos dê uma estrelinha para nos ajudar a divulgar o projeto.

As instruções de instalações estão no README.md de cada projeto.


## Desafio 1 - Vídeo 1

Desenvolva uma aplicação utilizando Golang que disponibilizará um servidor web na porta 8000.

Ao acessar deveremos ver uma página com o seguinte conteúdo:

- Background com um tema de um filme, quadrinhos, seriado a sua escolha
- De forma centralizada escreva: Imersão Full Cycle entre h1
- Fique na liberdade para estilizar a página a seu gosto
- Gere o arquivo executável da aplicação rodado: GOOS=linux go build main.go

Gere uma imagem Docker que ao ser executada rode a aplicação. Faça o push da imagem no Docker Hub.

OBS: Lembrando que para realizar o push no Docker Hub, sua imagem deve ser o seguinte padrão de nome: <seulogin>/nome-da-imagem.


## Desafio 2 - Vídeo 3

Nesse desafio você trabalhará com backend e frontend juntos para consolidar os conhecimentos adquiridos nas aulas de Nest.js e React.js.

Para isso:

- Crie um docker-compose.yaml que levante uma aplicação Nest.js e React juntos
- A aplicação Nest.js precisa rodar na porta 3000
- Aplicação React.js precisa rodar na porta 3001.
- Ao acessar http://localhost:3001 a aplicação React precisa consumir e listar "rotas" do endpoint do Nest.js: http://localhost:3000/routes.
- O endpoint http://localhost:3000/routes precisa retornar 5 rotas com os seguintes dados: title - título da rota, startPosition - contém latitude e longitude, endPosition - contém latitude e longitude


## Desafio 3 - Vídeo 5

Nesse desafio, você deverá gerar os manifestos yaml do Kubernetes (deployment e service) para o backend e o frontend que criados no desafio 2.

Você NÃO precisa utilizar um Cloud Provider como AWS, GCP e Azure para realizar essa tarefa. Você pode realizar localmente a instalação do cluster utilizando o Kind (https://kind.sigs.k8s.io/).

Crie uma pasta chamada k8s no seu repositório do github (utilizado no desafio anterior) e informe no campo abaixo.
