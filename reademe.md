# Documentação da API
Definir um local do computador para criar a pasta do projeto
```
mkdir NOME_PROJETO
```
Abrir a ppasta no VSCode
```
code .
```
Iniciar gerenciador de pacotes node
```
npm init -y
```
Criar o arquivo .gitignore
```
touch .gitignore
```
Criar o arquivo .env
```
touch .env
```
Instalar os pacotes para rodar a API
```
npm i express nodemon dotenv
```

* express: será o servidor da API
* nodemon: atualizar os arquivos alterados sem parar o servidor
* dotenv: gerenciador de variáveis de ambiente

Adicionar pastas e arquivos no .gitignore
```
node_modules
.env
```