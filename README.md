# Projeto Trybe Futebol Clube

## Contexto

Projeto criado durante o módulo de back-end do curso da [Trybe](https://www.betrybe.com/).
TFC é um site informativo sobre partidas e classificações de futebol. O front-end foi desenvolvido e fornecido pela Trybe, cabendo aos alunos (individualmente) construírem o back-end.

| ![Exemplo do front-end](/assets/front-example.png) |
|:--:|
| *O front-end foi fornecido pela [TRYBE](https://www.betrybe.com/) para o desenvolvimento do projeto. O back-end foi desenvolvido por [Ruan Cunha](https://github.com/RuanCunha).* |

## Tecnologias utilizadas

- Node.Js
- Express
- Sequelize
- REST
- Docker

# Como rodar

> Na sua máquina você deve ter:
>
> - Sistema Operacional Distribuição Unix (Ubuntu, Debian, Pop_OS...)
> - Node versão 16
> - Docker
> - Docker-compose versão 1.29.2

1. Clone o repositório e acesse a pasta com o comando:
* `git clone git@github.com:RuanCunha/project-trybe-futebol-clube.git && cd project-trybe-futebol-clube`
2. Instale as dependências:
* `npm install`
3. Crie as imagens e suba as aplicações para o compose usando o comando:
* `npm run compose:up`
4. Acesse a pasta do back-end e monte a aplicação com o comando:
* `cd app/backend && npm run build`
5. Acesse pelo navegador o endereço local:
* `http://localhost:3000/`

## Executando os testes

Execute os testes do back-end utilizando o comando:

* `npm test`

## Próximos passos (Roadmap)

- [X]  Adicionar instruções de instalação e execução local
- [ ]  Hospedar e disponibilizar online
- [ ]  Criar frontend original para substituir o da Trybe
