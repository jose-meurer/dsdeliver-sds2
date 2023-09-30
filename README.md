
# DS Delivery 
[![Netlify Status](https://api.netlify.com/api/v1/badges/d07d0993-0bc3-458e-9d5a-0899add98ff3/deploy-status)](https://app.netlify.com/sites/josemeurersds2/deploys)

# Sobre o projeto

https://josemeurersds2.netlify.app/


DS Delivery é uma aplicação full stack web e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema de pedido e entrega de restaurante. Os dados da solicitação do pedido são coletados via web e posteriormente os pedidos são entregues e confirmados no app mobile.

## Layout mobile
![Mobile 1](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/HomeAndroid.jpg) 
![Mobile 2](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/OrderAndroid.jpg) 
![Mobile 3](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/OrderDetailsAndroid.jpg)

## Layout web
![Web 1](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/HomeDesktop.png)

![Web 2](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/OrderDesktop1.png)

![Web 3](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/OrderDesktop2.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/jose-meurer/dsdeliver-sds2/blob/main/ImageProject/Image/sds2/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## API
- Mapbox
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/Josewm18/dsdeliver-sds2.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

## Front end mobile
Pré-requisitos: npm / expo

```bash

# entrar na pasta do projeto front end web
cd front-mobile

# instalar dependências
expo install @react-navigation/stack @react-native-community/masked-view react-native-screens react-native-gesture-handler @react-navigation/native expo-app-loading @expo-google-fonts/open-sans expo-font

# executar o projeto
npm start
```

# Autor

[José Meurer](https://www.linkedin.com/in/jose-walter-meurer-1b24241b6/)
