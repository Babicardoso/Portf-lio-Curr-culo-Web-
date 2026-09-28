# 🌐 Desafio HTML5 Semântico: Página de Portfólio / Apresentação

## 🎯 Sobre o Projeto

Este projeto consiste em uma página web responsiva e estruturada utilizando **HTML5 semântico puro**, desenvolvida a partir de um modelo de layout de apresentação/portfólio. 

O foco principal do desafio foi aplicar as melhores práticas de estruturação web, acessibilidade e utilização correta de tags semânticas, tabelas estruturadas e formulários organizados.

---

## 📝 Requisitos & Funcionalidades Implementadas

### ✅ Estrutura & Navegação Semântica
- **Cabeçalho (`<header>`):** Título principal com identificação e menu de navegação (`<nav>`).
- **Navegação Interna:** Links de ancoragem (`href="#id"`) para transição suave entre as seções:
  - `#sobre` — Sobre Mim
  - `#projetos` — Meus Projetos
  - `#contato` — Entre em Contato

### 👤 Seção "Sobre Mim" (`<section id="sobre">`)
- Foto de perfil formatada nas dimensões exatas de **150x150px**.
- Parágrafos de apresentação pessoal e profissional.
- Lista estruturada com as principais **Habilidades Técnicas**.

### 💼 Seção "Meus Projetos" (`<section id="projetos">`)
- Tabela semântica (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) contendo 4 colunas:
  1. **Projeto**
  2. **Tecnologias**
  3. **Status**
  4. **Link** (com hiperlinks funcionais)

### ✉️ Seção "Entre em Contato" (`<section id="contato">`)
- Formulário de contato envolto na tag `<fieldset>` com legenda (`<legend>Dados do Contato</legend>`).
- Todos os campos com rótulos (`<label>`) devidamente associados via atributo `for`:
  - Campo de texto para **Nome**
  - Campo de e-mail para **E-mail**
  - Menu suspenso (`<select>`) para escolha do **Assunto**
  - Área de texto (`<textarea>`) para **Mensagem**
  - Botão de envio (`<button type="submit">`)

### 📌 Rodapé (`<footer>`)
- Direitos autorais utilizando a entidade de caractere especial HTML (`&copy;`).
- Informações de e-mail e telefone de contato.

---

## 🔧 Especificações Técnicas

- **Linguagem:** HTML5 Semântico
- **Semântica utilzada:** `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<fieldset>`, `<legend>`, `<footer>`
- **Acessibilidade:** Relação 1:1 entre `<label>` e `<input>`/`<select>`/`<textarea>`, atributo `alt` em imagens e links estruturados.
