Este repositório contém testes automatizados para APIs e aplicações web utilizando **Cypress** e **Postman**, com geração de relatórios visuais via **Mochawesome**.

---

## 🔧 Tecnologias Utilizadas

- ✅ [Cypress](https://www.cypress.io/) – Testes de ponta-a-ponta e API
- 📬 [Postman](https://www.postman.com/) – Testes e validações de requisições HTTP
- 📊 [Mochawesome](https://github.com/adamgruber/mochawesome) – Relatórios HTML dos testes
- 💻 Node.js e NPM – Gerenciamento do projeto

---

## 📁 Estrutura do Projeto

```bash
qa-web-tests/
├── cypress/
│   ├── e2e/                    # Testes automatizados
│   ├── reports/                # Relatórios em HTML (gerados automaticamente)
│   └── support/                # Arquivos de configuração e hooks
├── postman/                    # Coleções e ambiente do Postman (opcional)
├── cypress.config.js           # Configuração principal do Cypress
├── README.md                   # Documentação do projeto
└── package.json                # Dependências e scripts do projeto
```

---

## 🚀 Como Executar os Testes

### ▶️ Cypress com Interface Gráfica

```bash
npx cypress open
```

Escolha o teste e execute no navegador com visualização dos passos em tempo real.

---

### 🧪 Cypress em Modo Headless + Relatório

```bash
npx cypress run
```

Relatórios são gerados automaticamente na pasta:

```
cypress/reports/mochawesome.html
```

---

## 📊 Exemplo de Relatório

Após rodar os testes, abra o arquivo `mochawesome.html` para visualizar:

- ✅ Passos que passaram
- ❌ Falhas detalhadas
- 🕒 Tempo de execução
- 📄 Corpo das requisições/respostas

---

## 🌐 Teste com Postman

Se o projeto também usar **coleções do Postman**:

1. Abra o Postman
2. Importe os arquivos `.json` na pasta `/postman`
3. Execute a coleção ou configure no CI/CD

---

## 💡 Comandos úteis

```bash
# Instalar dependências
npm install

# Rodar testes com relatório
npx cypress run

# Abrir interface gráfica do Cypress
npx cypress open
```

---

## 📌 Requisitos

- Node.js 16+
- Git
- NPM
- Navegador (Chrome, Edge, etc.)

---

## 🧠 Contribuindo

Sinta-se à vontade para abrir issues ou pull requests com melhorias nos testes, estrutura ou cobertura de APIs.

---

## 🧑‍💻 Autor

**Ricardo Tormen**
