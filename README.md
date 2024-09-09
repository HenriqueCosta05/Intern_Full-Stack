# Case Técnico - Full-Stack


<img src="./sample.png" alt="Sample" />

Esse case técnico teve como objetivo a avaliação das habilidades de código para vaga de **estágio como desenvolvedor full-stack**, ofertada pela empresa Jack Experts.

Toda a documentação está disponível neste repositório, enquanto o código foi separado em diferentes repositórios - frontend e backend.

## Front-end
[Link do Repositório](https://github.com/HenriqueCosta05/Intern_Front-End.git)

## Back-end
[Link do Repositório](https://github.com/HenriqueCosta05/Intern_Back-End)

##  Figma (Protótipo)
[Link do Figma](https://www.figma.com/design/VqqhUUeVNcn7kpOJASZv4K/Jack-Experts?node-id=0-1&t=qkv3iFXUlMIPWdhX-1)
### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas para as seguintes tarefas:

- [ ] Cobertura completa de testes (em andamento)
- [ ] Melhoria na performance da aplicação web (em andamento)

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente do `Node.js e NPM`.
- Você instalou o banco de dados `MySQL` (confira como instalar [aqui](https://dev.mysql.com/downloads/installer/))


## 🚀 Instalando o projeto

Para instalar o Case técnico, siga estas etapas:

### Front-end

```
    git clone https://github.com/HenriqueCosta05/Intern_Front-End.git
```

```
    npm install
```

```
    npm run dev
```

### Back-end

> Observação: no projeto foram utilizadas as seguintes variáveis de ambientes, a serem adaptadas pelo desenvolvedor:

DATABASE_URL=""

JWT_SECRET=""

JWT_REFRESH_SECRET=""


```
    git clone https://github.com/HenriqueCosta05/Intern_Back-end.git
```

```
    npm install
```

 Após a instalação das dependências, devemos criar um banco de dados respectivo com o MYSQL, executando o seguinte comando:

```
    CREATE DATABASE users;
```

Para esse projeto, fiz uso do `Prisma` como ORM de banco de dados. Portanto, para executar as alterações realizadas com essa ferramenta, execute o comando:

```
    prisma migrate dev --name init
```

Após a sincronização com o banco de dados, devemos realizar o seguinte comando, para inicializar o NestJS:

```
    npm run start:dev
```


## Jornada do Usuário