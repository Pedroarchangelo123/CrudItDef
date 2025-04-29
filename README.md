
# 🛠️ Projeto CRUD com React

Este é um projeto simples de CRUD (Create, Read, Update, Delete) desenvolvido com **React** e **React-Bootstrap**, com armazenamento local via **localStorage**. O objetivo é permitir o cadastro, edição, exclusão e listagem de produtos de forma prática.

## 🚀 Deploy

🔗 Acesse o projeto online: [https://cruditproducts.netlify.app](https://cruditproducts.netlify.app)

---

## 📁 Estrutura de Pastas

```plaintext
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── ProdutoForm.jsx
│   │   └── ProdutoLista.jsx
│   ├── Service/
│   │   └── ProdutoService.js
│   ├── App.js
│   ├── index.js
│   └── App.css
├── package.json
└── README.md
```

---

## ⚙️ Funcionalidades

- ✅ Adicionar produtos com nome, categoria e preço
- ✅ Listar produtos cadastrados em uma tabela
- ✅ Editar produtos existentes
- ✅ Excluir produtos com confirmação
- ✅ Armazenamento persistente com **localStorage**
- ✅ Interface responsiva com **React-Bootstrap**

---

## 🧪 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [UUID](https://www.npmjs.com/package/uuid) para geração de IDs únicos
- [LocalStorage](https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage)

---

## 🖼️ Responsividade

O layout utiliza classes responsivas e media queries para garantir usabilidade em dispositivos móveis.  
A tabela centralizada e os botões são adaptados para telas menores.

---

## 📝 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seuusuario/seurepo.git

# Acesse a pasta
cd seurepo

# Instale as dependências
npm install

# Rode o projeto
npm start
```

---

## 👥 Integrantes

- Pedro Archangelo  
- Yago  
- Ana Beatriz

---

## 🤝 Contribuição

Este projeto foi desenvolvido como exercício em grupo. Sinta-se à vontade para clonar, modificar e usar como base para seus estudos!

---

## 📌 Observações

- Todos os dados são armazenados no navegador via `localStorage`.
- Ao atualizar a página, os dados permanecem salvos.
- Não há integração com banco de dados externo.

---

Feito com ❤️ por Pedro, Yago e Ana Beatriz
