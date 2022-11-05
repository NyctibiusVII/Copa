<h1 align="center">
    <img src="./.github/logo-full.png" width="350" alt="Logo copa">
</h1>
<h4 align="center">
    Trilha Ignite<br><img src="./.github/logo-ignite.svg" height="48" alt="Logo Ignite">
</h4>
<!-- <h4 align="center">Projeto web construído durante o Next Level Week #10-Ignite com a Rocketseat/DiegoFernandes | Rodrigo Gonçalves.</h4> -->
<p align="center">
    <img alt="Plataforma" src="https://img.shields.io/static/v1?label=Plataforma&message=Mobile/PC&labelColor=192922&color=F7DD43">
    <a href="https://lp.rocketseat.com.br/nlw">
        <img alt="copa" src="https://img.shields.io/badge/copa-NLW 10-333?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg==&labelColor=192922&color=F7DD43"></img>
    </a>
    <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/NyctibiusVII/copa?labelColor=192922&color=F7DD43">
    <a href="https://github.com/NyctibiusVII/copa/blob/main/LICENSE">
        <img alt="Licença" src="https://img.shields.io/static/v1?label=License&message=MIT&labelColor=192922&color=F7DD43">
    </a>
    <a href="https://picpay.me/Matheus_nyctibius_vii">
        <img alt="Donate" src="https://img.shields.io/static/v1?label=$&message=Donate&labelColor=F7DD43&color=F7DD43">
    </a>
</p>
<p align="center">
    <a href="#copa-">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#tecnologias-">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#layout-">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#licença-%EF%B8%8F">Licença</a>
</p>
<!--
<p align="center">
    <a href="README.md">Inglês</a>
    ·
    <a href="README-pt.md">Português</a>
</p>
-->

# Copa <img src="./.github/logo-icon.png" width="28" alt="Logo icon Ignite">
Projeto desenvolvido para dar palpites e fazer bolões em grupo de jogos das copa. Projeto realizado na Next Level Week #10 @Rocketseat.

#### Funcionalidades
* Bolão dos jogos
* Listagem de jogos da copa 2022
* Grupos para dar palpites
* Compartilhamento dos grupos
* Ranking dos participantes

## Tecnologias 🚀
Esse projeto foi desenvolvido com as seguintes tecnologias:
<details>
    <summary>WEB___</summary>
    <a href='https://reactjs.org'>React</a><br>
    <a href='https://tailwindcss.com/'>Tailwindcss</a><br>
    <a href='https://www.typescriptlang.org'>Typescript</a>
</details>
<details>
    <summary>NODE___</summary>
    <a href='https://nodejs.org/pt-br'>Node</a><br>
    <a href='https://www.prisma.io'>Prisma</a><br>
    <a href='https://www.typescriptlang.org'>Typescript</a>
</details>
<details>
    <summary>MOBILE___</summary>
    <a href='https://expo.dev'>Expo</a><br>
    <a href='https://reactnative.dev'>React Native</a><br>
    <a href='https://www.typescriptlang.org'>Typescript</a><br>
    <a href='https://axios-http.com/docs/intro'>Axios</a>
</details>

## Layout 🚧
### Desktop Screenshot
<div style="display: flex; flex-direction: 'column'; align-items: 'center';">
    <img width="580px" src="./.github/desktop.png">
</div>

### Mobile Screenshot
<div style="display: flex; flex-direction: 'row';">
    <img width=180px" src="./.github/mobile.png">
</div>
    <!-- IMGS
      ------------------------------
      Web
      Mobile
      ------------------------------
    -->

## Rodando o projeto 🚴🏻‍♂️
#### "Só vou dar uma olhadinha...":
  <a href="https://copa-nyctibiusvii.vercel.app">💬 Site hospedado na Vercel 📋</a>

#### Na sua maquina:
<details>
    <summary>Dependências</summary>

```json
  ------- WEB -------
  "dependencies": {
    "@types/node": "18.11.9",
    "@types/react": "18.0.24",
    "@types/react-dom": "18.0.8",
    "axios": "^1.1.3",
    "eslint": "8.26.0",
    "eslint-config-next": "13.0.1",
    "next": "13.0.1",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "typescript": "4.8.4"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.13",
    "postcss": "^8.4.18",
    "tailwindcss": "^3.2.1"
  }

  ------- NODE -------
  "dependencies": {
    "@fastify/cors": "^8.1.1",
    "@fastify/jwt": "^6.3.2",
    "@prisma/client": "^4.5.0",
    "axios": "^1.1.3",
    "fastify": "^4.9.2",
    "short-unique-id": "^4.4.4",
    "zod": "^3.19.1"
  },
  "devDependencies": {
    "@mermaid-js/mermaid-cli": "^9.1.7",
    "prisma": "^4.5.0",
    "prisma-erd-generator": "^1.2.2",
    "tsx": "^3.11.0",
    "typescript": "^4.8.4"
  }

  ------- MOBILE -------
  "dependencies": {
    "@expo-google-fonts/roboto": "^0.2.2",
    "@react-navigation/bottom-tabs": "^6.4.0",
    "@react-navigation/native": "^6.0.13",
    "@types/react": "~18.0.0",
    "@types/react-native": "~0.69.1",
    "axios": "^1.1.3",
    "country-list": "^2.2.0",
    "dayjs": "^1.11.6",
    "expo": "~46.0.16",
    "expo-auth-session": "^3.7.1",
    "expo-font": "^10.2.1",
    "expo-random": "^12.3.0",
    "expo-status-bar": "~1.4.0",
    "expo-web-browser": "^11.0.0",
    "native-base": "^3.4.21",
    "phosphor-react-native": "^1.1.2",
    "react": "18.0.0",
    "react-native": "0.69.6",
    "react-native-country-flag": "^1.1.9",
    "react-native-safe-area-context": "4.3.1",
    "react-native-screens": "~3.15.0",
    "react-native-svg": "12.3.0",
    "typescript": "^4.6.3"
  },
  "devDependencies": {
    "@babel/core": "^7.12.9",
    "@types/country-list": "^2.1.1",
    "babel-plugin-inline-dotenv": "^1.7.0",
    "dotenv": "^16.0.3",
    "react-native-svg-transformer": "^1.0.0"
  }
```
> Ex: `$ npm install _____` ou `$ yarn add _____` para instalar as dependências

> Utilize a tag `-D` para instalar as dependências de desenvolvimento.<br>
> Utilize a tag `@types` para instalar o suporte a Typescript.<br>
> Utilize a tag `@latest` para instalar a versão mais recente.
</details>

```bash
# Clone o repositório
$ git clone https://github.com/NyctibiusVII/copa.git

# Acesse a pasta do projeto no terminal
$ cd copa

# Acesse a pasta do sub-projeto no terminal:
$ cd web                         # Projeto ReactJS
$ cd server                      # Projeto NodeJS
$ cd mobile                      # Projeto React Native

# Instale as dependências com o gerenciador de pacotes de sua preferência
$ npm install   /   yarn add     # Serve para ReactJS, NodeJS e React Native

# Execute o sub-projeto:
# ---------- PARA WEB ---------- #
$ npm run dev   /   yarn dev     # Para rodar o projeto Web (Frontend)

# --------- PARA NODE ---------- #
$ npm run dev   /   yarn dev     # Para rodar o projeto Node (Backend)

# -------- PARA MOBILE --------- #
$ npm run start   /   yarn start # Para o projeto Mobile (Frontend Mobile)

# O ReactJS roda na porta: 3000
# O NodeJS roda na porta: 3333
# O React Native roda na porta: 19000

# Acesse http://localhost:$PORT *Ex: Cuidado para não ligar dois ou mais projetos na mesma porta, pois o servidor pode não iniciar.
```

## Contribuição 💭
Para construir essa aplicação tive a ajuda dos professores **Diego Fernandes** e **Rodrigo Gonçalves** da Rocketseat que disponibilizaram video aulas do projeto **copa** e ajudaram no ensino das<br>
- linguagens {<br>
&nbsp;&nbsp;&nbsp;&nbsp;ReactJS,<br>
&nbsp;&nbsp;&nbsp;&nbsp;NodeJS,<br>
&nbsp;&nbsp;&nbsp;&nbsp;React Native<br>
}

além também de ter a ajuda desta grande comunidade que a Rocketseat construiu no *Discord*.

Para ajudar no projeto confira a página de [contribuição](./CONTRIBUTING) para ver como começar uma discussão e começar a contribuir.

### Hashtags \#
| Dias  | Hashtags           |
|-------|--------------------|
| Dia 1 | #PlayStation       |
| Dia 2 | #Comprometimento   |
| Dia 3 | #Aceleracao        |
| Dia 4 | #Comunidade        |
| Dia 5 | #ProximoNivel      |

## Licença ⚖️
Este projeto está sob a licença do MIT. Veja o arquivo [LICENSE](https://github.com/NyctibiusVII/copa/blob/main/LICENSE) para mais detalhes.

## Contato ✉️
| [![Matheus Vidigal](https://github.com/NyctibiusVII.png?size=100)](https://github.com/NyctibiusVII) |
| :---: |
| <sub>[Matheus Vidigal](https://github.com/NyctibiusVII)</sub> |

<p align="left">
    <a href="https://www.linkedin.com/in/matheus-vidigal-nyctibiusvii/">
        <img alt="Matheus Vidigal / Linkedin" src="https://img.shields.io/badge/-Matheus Vidigal-333?style=flat&logo=Linkedin&logoColor=fff&color=192922" />
    </a>
    <a href="https://mail.google.com/mail/u/1/#inbox?compose=GTvVlcSGLCKpKJfwPsKKqzXBplKkGtCLvCQcFWdWxCxQFfkHzzjVkgzrMFPBgKBmWFHvrjrCsMqSH">
        <img alt="Matheus Vidigal / Linkedin" src="https://img.shields.io/badge/-Matheus Vidigal-333?style=flat&logo=Gmail&logoColor=ffffff&color=F7DD43" />
    </a>
</p>