# Next Level Week #3 | Rocketseat

O **NLW (Next Level Week)**, em tradução livre, Semana do Próximo Nível, é um evento virtual organizado e realizado pela **[Rockeseat](https://rocketseat.com.br/)** com o intuito de elevar os conhecimentos e habilidades de Devs em apenas uma semana.

A 3º edição do evento, ocorreu entre os dias 12 e 16 de Outubro, no qual foi proposto e realizado o desenvolvimento do projeto **Happy**, tanto aplicação web como mobile, utilizando ReactJS.

## Menu

## Cronograma

### 1º Dia | Conceitos e Estrutura Web

[X] Apresentação do projeto
[X] Ambiente de desenvolvimento
[X] Conceitos de back-end, front-end e API
[X] O que é React e por que utilizar?
[X] Por que vamos utilizar Typescript?
[X] Criando projeto com ReactJS
[X] Componentes, JSX e propriedades
[X] Criando a landing page
[X] Trabalhando com rotas
[X] Página com mapa

### 2º Dia | Back-end com Node.js

[X] Criando projeto com Node.js
[X] Rotas, parâmetros e métodos HTTPS
[X] Configurando banco de dados
[X] Criando orfanato sem imagem
[X] Abstraindo em controller
[X] Listando orfanatos
[X] Upload de imagens
[X] Trabalhando com views
[X] Detalhe do orfanato
[X] Lidando com exceções
[X] Validação de dados

### 3º Dia | Finalizando front-end

[X] Finalizando página de mapa
[X] Copiando páginas faltantes
[X] Criando navegação entre telas
[X] Abstraindo componentes
[X] Conectando front-end com back-end
[X] Listando orfanatos no map
[X] Detalhe do orfanato
[X] Criação de um orfanato

### 4º Dia | Estruturando App Mobile

[X] 

### 5º Dia | Finalizando App Mobile

## Ambiente de Desenvolvimento

- Node.js + NPM
- Yarn
- Expo
- Visual Studio Code

Para baixar, instalar e configurar o ambiente, acesse o guia **[Configurando Ambiente](https://www.notion.so/Configurando-o-ambiente-953aad022cda4fbcb149be2bfe793995)** desenvolvido pela própria [Rockeseat](https://rocketseat.com.br/).

## Tecnologias Utilizadas

- Yarn
- Notion
- Figma
- Insomnia
- Beekeeper Studio

## Start

Para iniciar o desenvolvimento da aplicação web, executa-se o seguinte comando:

```
yarn create react-app web --template typescript
```

ou

```
npx create-react-app web --template typescript
```


Add ícones
```
yarn add react-icons
```

Add router
```
yarn add react-router-dom
```

Add tipagem router versão dev
```
yarn add @types/react-router-dom -D
```

Add mapa leaflet
```
yarn add leaflet react-leaflet
```

Add tipagem mapa leaflet
```
yarn add @types/react-leaflet
```

Add express
```
yarn add express
```

Add tipagem express
```
yarn add @types/express -D
```

Add typescript
```
yarn add typescript -D
```

Cria arquivo tsconfig.json
```
yarn tsc --init
```

Add pacote ts-node-dev como dependência de desenvolvimento (-D)
```
yarn add ts-node-dev -D
```

Add pacote banco de dados
```
yarn add typeorm sqlite3
```

Pacote para lidar com upload de imagens (arquivos em geral):
Add biblioteca multer
```
yarn add multer
```

Tratativa de exceções:
Add biblioteca express-async-errors
```
yarn add express-async-errors
```

Validação de Dados:
Add biblioteca yup
```
yarn add yup
```

Add tipagem yup
```
yarn add @types/yup -D
```

Permitir requisições de outros domínios:
Add módulo cors
```
yarn add cors
```

Add tipagem cors
```
yarn add @types/cors -D
```

Biblioteca para conectar (fazer requisições) front-end com a API (back-end)
Add axios
```
yarn add axios
```

MOBILE

Ferramenta Expo
Add Expo
```
yarn global add expo-cli
```

Iniciar projeto mobile
```
expo init mobile
```