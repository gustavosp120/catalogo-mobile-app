# 📱 Catálogo Mobile - Projeto React Native

Aplicativo desenvolvido como projeto final da disciplina **Mobile Development**, com foco em consumo de API REST, navegação entre telas, e gestão de estado com Redux Toolkit.

---

## 🚀 Funcionalidades

- Tela de **login simulada** com validação
- Lista de produtos divididos por **categorias masculinas e femininas**
- **Consumo da API** [DummyJSON](https://dummyjson.com/)
- Visualização de **detalhes do produto** (descrição, imagem, preço, desconto)
- Botão de **logout**
- Estrutura organizada com **Redux Toolkit** e **Axios**

---

## 🧠 Tecnologias Utilizadas

- [React Native (Expo)](https://expo.dev/)
- [Axios](https://axios-http.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React Navigation](https://reactnavigation.org/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 📦 Estrutura do Projeto

```bash
📁 src/
├── components/         # Componentes reutilizáveis
├── screens/            # Telas: Login, Produtos, Detalhes
├── services/           # API (Axios)
├── store/              # Redux Toolkit (slices, store)
└── styles/             # Estilizações (separadas por tela)
