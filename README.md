# 🐾 ONG Patas Amigas — Single Page Application (SPA)

> **Proposta Acadêmica:** Aplicação web desenvolvida para a disciplina de **Desenvolvimento Front-End**, focada no uso de JavaScript ES6+, arquitetura SPA, controle de versão profissional e diretrizes de acessibilidade (WCAG 2.1 Nível AA).

---

## 🎯 Objetivo do Projeto

Desenvolver uma plataforma web dinâmica para a ONG **Patas Amigas**, resolvendo demandas de adoção responsável, captação de doações e cadastro de voluntários.

A plataforma oferece:
* **Navegação Dinâmica (SPA):** Transição fluida entre seções sem recarregamento de página via evento `popstate`.
* **Adoções e Histórias:** Injeção dinâmica de dados de pets e projetos diretamente no DOM.
* **Formulários Interativos:** Validação reativa com feedback visual e confirmação de cadastro/doação.
* **Persistência Local:** Salvamento e recuperação de doações e cadastros usando `localStorage`.

---

## 🛠️ Tecnologias e Arquitetura

* **HTML5 Semântico & ARIA:** Estrutura focada em SEO e acessibilidade por leitor de tela e teclado.
* **CSS3 Modular:** Estilização responsiva, regras de foco navegável e alto contraste visual.
* **JavaScript ES6+ (Vanilla):** Módulos ES6 (`import`/`export`), manipulação de DOM e rotas.
* **SweetAlert2 (via CDN):** Modal e alertas interativos para confirmação de ações do usuário.
* **Git, GitHub & GitFlow:** Controle de versão com branches `main`, `develop` e `feature/`, commits semânticos e tags SemVer.

---

## 📁 Estrutura do Repositório

```text
/
├── css/
│   └── styles.css        # Estilos globais e componentes visuais
├── js/
│   ├── app.js            # Ponto de entrada e inicialização da aplicação
│   ├── router.js         # Gerenciamento de rotas e navegação SPA
│   └── storage.js        # Camada de persistência no localStorage
├── img/                  # Imagens e assets otimizados para web
├── index.html            # Estrutura base da SPA (ponto de entrada)
└── README.md             # Documentação técnica do projeto
