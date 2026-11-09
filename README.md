# 💭 Memoteca

Aplicativo organizador de pensamentos e frases. Permite cadastrar, listar, editar e excluir pensamentos, com conteúdo e autoria, consumindo uma API REST.

<p align="center">
  <img src="prints/memoteca.gif" alt="Demonstração da Memoteca" width="720" />
</p>

<p align="center">
  <a href="https://memoteca-pearl.vercel.app"><b>🚀 Ver o projeto online</b></a> ·
  <a href="https://www.figma.com/community/file/1418667851533626562/javascript-implementando-crud-com-requisicoes-http-memoteca">🎨 Figma</a> ·
  <a href="https://cursos.alura.com.br/course/javascript-implementando-crud-requisicoes-http">📚 Curso</a>
</p>

## Funcionalidades

- **Cadastrar** pensamentos com conteúdo e autoria
- **Listar** os pensamentos salvos, com aviso de lista vazia
- **Editar** um pensamento existente
- **Excluir** pensamentos da lista

## Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

- **JavaScript** organizado em módulos: `api.js` (requisições), `ui.js` (interface) e `main.js` (eventos)
- **Fetch API e Axios** para as requisições HTTP (GET, POST, PUT e DELETE)
- **JSON Server** simulando o back-end REST

## Como rodar

Você vai precisar do Node.js.

```bash
git clone https://github.com/DanielBarret0/memoteca.git
cd memoteca/backend
npm install -g json-server
npm start
```

A API sobe em http://localhost:3000.

Para o front-end, abra o projeto no VS Code e use a extensão **Live Server** no `index.html`. O site abre em http://localhost:5500.

---

Feito por [Daniel Barreto](https://www.linkedin.com/in/daniel-barreto-developer) · [Portfólio](https://portifoliodaniel.vercel.app/)
