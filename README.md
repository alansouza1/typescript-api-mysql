# Sobre o Projeto

Neste projeto foi desenvolvida uma loja de itens medievais, no formato de uma _API_, utilizando _TypeScript_.

O projeto foi desenvolvido utilizando as camadas _Models_, _Services_ e _Controllers_(_MSC_).

Foram criados alguns _endpoints_ que irão ler e escrever em um banco de dados, utilizando o **MySQL**.

Para o cadastro de usuários foi utilizado o _JWT(JSON Web Token)_ para gerar um _token_ de autenticação e autorização.

# Rodando o Projeto

### Requisitos:
- Node.js
- Docker
- Docker Compose

Depois de clonar o repositório instale as dependências do npm com o comando:
```
npm install
```
Inicie o docker utilizando o comando:
```
docker-compose up -d
```
Crie o banco de dados com o comando:
```sh
docker exec -it trybesmith npm run restore
```
E por fim, inicie o servidor back-end com o comando:
```
docker exec -it trybesmith npm run dev
```
