# Boas-vindas ao repositório do projeto Docker Todo List!
<details>
  <summary><strong>👨‍💻 O que foi desenvolvido</strong></summary>

Habilidades desenvolvidas:

1. **_Conteinerizar_** aplicações;
2. Criar uma conexão entre elas;
3. Orquestrar seu funcionamento.

<summary><strong>‼️ Instalação do projeto:</strong></summary><br />

1. Clone o repositório
* `git clone git@github.com:git`
* Entre na pasta do repositório que você acabou de clonar:
  * `cd Docker-ToDo-List`

2. Instale as dependências:
  * `npm install`


3. Rode o comando `npm start` na pasta de back-end e front-end e acesse o projeto via browser, no caminho 'http://localhost:3000/'

<summary><strong>🛠 Testes</strong></summary><br />
# Em desenvolvimento.


# Escopo do projeto

Temos [uma aplicação full-stack](docker/todo-app) neste repositório: um **aplicativo de tarefas**! Esta aplicação precisava ser conteinerizada para funcionar. Você deverá desenvolver os arquivos de configuração para cada frente específica: `Front-end`, `Back-end` e, no nosso caso, para um aplicativo de `teste` que valida se as aplicações estão se comunicando.

## Comandos docker

### 1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12`

### 2. Inicie o container `01container`

### 3. Liste os containers filtrando pelo nome `01container`

### 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar à ele

### 5. Remova o container `01container`

### 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container

### 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro

### 8. Pare o container `02images` que está em andamento

## Dockerfile

### 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`

### 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`

### 11. Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`

## Docker-compose

### 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.

</details>
