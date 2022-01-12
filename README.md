# Projeto Jest Async Mock

Projeto desenvolvido durante o Curso de Desenvolvimento WEB, Turma 12, da [trybe](https://www.betrybe.com/), onde desenvolvi minhas habilidades em JavaScript e Jest na criação de testes para funções assíncronas.

---

## Trybe

A [trybe](https://www.betrybe.com/) é uma escola para pessoas que querem construir uma carreira de sucesso em tecnologia e que se compromete integralmente com seus estudantes, pois as pessoas só pagam quando conseguirem um bom trabalho.

O programa conta com mais de 1.500 horas de aulas presenciais e on-line e aborda introdução ao desenvolvimento de software, front-end, back-end, ciência da computação, engenharia de software, metodologias ágeis e habilidades comportamentais.

O currículo da Trybe foi desenhado em parceria com as maiores empresas de tecnologia do Brasil e do mundo e ao longo da formação, estudamos JavaScript, HTML, CSS, React, Node, Express.js, SQL, Git, entre outras linguagens e frameworks.

---

## Sumário

- [Habilidades desenvolvidas](#habilidades-desenvolvidas)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Requisitos do projeto](#requisitos-do-projeto)
  - [1 - Crie testes para uma função assíncrona](#1---crie-testes-para-uma-função-assíncrona)
  - [2 - Crie um "Mock" no arquivo test/mockFunctions.spec.js](#2---Crie-um-"Mock"-no-arquivo-test/mockFunctions.spec.js)
  - [3 - Crie um Mock para o retorno da API](#3---Crie-um-Mock-para-o-retorno-da-API)
  - [4 - Crie funções no arquivo test/setupTeardown.spec.js](#4---Crie-funções-no-arquivo-test/setupTeardown.spec.js)

---

## Habilidades desenvolvidas

- Escrever testes para funções assíncronas;
- Aplicar os seus conhecimentos acerca de testes utilizando o Jest;
- "Mockar" funções;
- "Mockar" APIs;

---

## Tecnologias utilizadas

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Jest](https://jestjs.io/pt-BR/)

---
## Requisitos do projeto

### 1 - Crie testes para uma função assíncrona

Complete os testes do arquivo `test/asyncJest.spec.js` para que funcionem com código assíncrono.

### 2 - Crie um "Mock" no arquivo test/mockFunctions.spec.js

Crie mock functions no arquivo `test/mockFunctions.spec.js` para que os testes mockados 'sobrescrevam' o código definido na pasta `src`. A idéia é que as funções criadas a partir do Jest tenham prioridade na sua execução.

### 3 - Crie um Mock para o retorno da API

Crie uma API mock no arquivo `test/mockApi.spec.js` para que os testes do Jest utilizem retornos de API fixos e independentes de requisições.

Exemplo de resposta da API randomuser.me:

```js

{
  gender: 'female',
  name: { title: 'Ms', first: 'Deborah', last: 'Hanson' },
  location: {
    street: { number: 1299, name: 'Rochestown Road' },
    city: 'Birr',
    state: 'Wicklow',
    country: 'Ireland',
    postcode: 16223,
    coordinates: { latitude: '26.2451', longitude: '45.2995' },
    timezone: {
      offset: '+5:30',
      description: 'Bombay, Calcutta, Madras, New Delhi'
    }
  },
  email: 'deborah.hanson@example.com',
  login: {
    uuid: '45db2b1f-1c9a-4a80-9572-e46614f86c30',
    username: 'bluewolf366',
    password: 'iverson3',
    salt: 'XKOOGc2x',
    md5: '8cb7b4686f3869247b3ed189de780ea6',
    sha1: 'c24641f415cf36f4494ea4007fb3d77b47a6aad5',
    sha256: 'a7bdd079ead0adf21f30cee5b94e5581a9fa0d5fc8b3c1881dbc864dabc55a80'
  },
  dob: { date: '1965-10-01T06:35:49.694Z', age: 55 },
  registered: { date: '2009-02-11T05:48:39.772Z', age: 11 },
  phone: '021-953-7205',
  cell: '081-160-6277',
  id: { name: 'PPS', value: '0109675T' },
  picture: {
    large: 'https://randomuser.me/api/portraits/women/7.jpg',
    medium: 'https://randomuser.me/api/portraits/med/women/7.jpg',
    thumbnail: 'https://randomuser.me/api/portraits/thumb/women/7.jpg'
  },
  nat: 'IE'
}

```

### 4 - Crie funções no arquivo test/setupTeardown.spec.js

Intercale funções entre os testes definidos no arquivo `test/setupTeardown.spec.js`.

---