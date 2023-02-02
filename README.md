# GuitarLA Strapi

### Features
- [x] Conexão com banco de dados PostgreSQL
- [x] Armazenamento de mídia utilizando Cloudinary
- [x] Criação do Collection Type Guitar
- [x] Criação do Collection Type Post
- [x] Criação do Single Type Course  

##

### Pré-requisitos:

Collection Type Guitar
- name
- description
- image
- price
- uid

<br />

Collection Type Post
- title
- content
- image
- uid

<br />

Single Type Course
- title
- content
- image

<br />

OBS: Utilize um banco de dados de sua preferência e configure o arquivo database.js

##

### Inicialização

Para realizar a instalação dos pacotes:
```
npm install
```

Rodar aplicação:
```
npm run develop
```

##

### Ferramentas Utilizadas

- Strapi
- Cloudinary
- PostgreSQL

##

Essa REST API foi desenvolvida para o projeto <a href="https://github.com/vselei/guitarla-remix">GuitarLA</a>
