<h1 align="center">Next Level Week Return - Widback - Servidor da aplicação</h1>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=NLW&message=Return&color=E51C44&labelColor=0A1033" alt="NLW Return" />
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033">
</p>


<br>

<h3 align="center">Prévia do NLW Return</h3>

![cover](.github/widget-nlwreturn.png?style=flat)

<br>

## 💻 Projeto
Widget para adicionar feedbacks que permite capturar a imagem aparente na tela e anexar ao feedback. Permitindo reportar bugs, partilhar novas ideias ou o que desejar. 

Este é um projeto desenvolvido durante a **[Next Level Week Return](https://nextlevelweek.com/)**, apresentada dos dias 01 a 08 de Maio de 2022.

## 🧪 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Nodejs](https://nodejs.org/en/)
- [Prisma](https://www.prisma.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [TypeScript](https://www.typescriptlang.org/)

## 🚀 Como executar

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/Jonathan-Rios/nlw-return-widback-server.git
$ cd nlw-return-widback-server
```

Para iniciá-lo, siga os passos abaixo:
```bash
# Instalar as dependências
$ npm install

# Iniciar o projeto
$ npm run start

# Iniciar o projeto em desenvolvimento
$ npm run dev
```
O servidor estará disponível pelo endereço http://localhost:3333. e só consta com uma rota do tipo <i>POST</i>:

http://localhost:3333/feedbacks.

Onde se espera um Body <strong>JSON</strong> do seguinte formato, sendo screenshot opcional:

```json
{
  "type": "BUG",
  "comment": "Relatando um bug encontrado.",
  "screenshot": "data:image/png;base641241231241231241512312"
}
```

Caso queira ver em funcionamento total, veja as aplicações: [Web](https://github.com/Jonathan-Rios/nlw-return-widback-web.git) [Mobile](https://github.com/Jonathan-Rios/nlw-return-widback-mobile.git)

## 🔖 Layout ( Front-end )

Você pode visualizar o layout do projeto através do link abaixo:

- [Layout Web](https://www.figma.com/community/file/1102912516166573468) 

Lembrando que você precisa ter uma conta no [Figma](http://figma.com/).

## 📝 License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE.md) para mais detalhes.

<br />

---
<br />

<a href="https://github.com/Jonathan-Rios">
 <img src="https://github.com/Jonathan-Rios.png" width="100px;" alt="" />
 <br />
 <sub><b>Jonathan Rios Sousa</b></sub></a>

#NeverStopLearning

[![Linkedin Badge](https://img.shields.io/badge/-Jonathan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonathan-rios-sousa-19b3431b6/)](https://www.linkedin.com/in/tgmarinho/) 
[![Gmail Badge](https://img.shields.io/badge/-jonathan.riosousa@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jonathan.riosousa@gmail.com)](mailto:jonathan.riosousa@gmail.com)