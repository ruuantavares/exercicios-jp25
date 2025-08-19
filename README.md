 # 📘 README - HTML  

## 🔹 Estrutura Básica
- `<!DOCTYPE html>` → define o tipo de documento (HTML5).  
- `<html lang="pt-br">` → define o idioma da página.  
- `<head>` → contém metadados da página.  
  - `<title>` → título exibido na aba do navegador.  
  - `<meta name="description">` → ajuda em SEO e descrição da página.  

## 🔹 Estrutura de Conteúdo
- `<header>` → cabeçalho com título e introdução.  
- `<main>` → conteúdo principal da página.  
- `<section>` → divide o conteúdo em blocos temáticos (perguntas, tabelas, feedback).  
- `<footer>` → rodapé com créditos e links.  

## 🔹 Texto e Semântica
- `<h1> a <h2>` → hierarquia de títulos, melhora acessibilidade e SEO.  
- `<p>` → parágrafos de texto.  
- `<strong>` → destaque semântico (importância).  
- `<em>` → ênfase em palavras.  
- `<abbr>` → acrônimos com significado (ex.: HTML, CSS).  
- `<br>` → quebra de linha (usar só quando necessário).  
- `<details>` e `<summary>` → conteúdo oculto expansível (ex.: respostas).  
- `<ol>` / `<ul>` → listas ordenadas e não ordenadas.  
- `<li>` → itens da lista.  
- `<figure>` e `<figcaption>` → imagem com legenda.  

## 🔹 Formulários
- `<form>` → cria formulários.  
- `<input>` → vários tipos:  
  - `radio` → escolha única.  
  - `checkbox` → múltipla escolha.  
  - `text`, `email`, `password`, `date`, `file`.  
- `<label>` → associa texto a inputs (boa prática de acessibilidade).  
- `<select>` + `<option>` → menus suspensos.  
- `<textarea>` → campo de texto longo.  
- `<fieldset>` e `<legend>` → agrupam inputs de forma semântica.  
- `<button>` → envia ação (ex.: feedback).  

## 🔹 Tabelas
- `<table>` → cria tabela.  
- `<thead>`, `<tbody>`, `<tfoot>` → separam cabeçalho, corpo e rodapé da tabela.  
- `<th>` → cabeçalhos das colunas.  
- `<td>` → células de dados.  
- Atributo `colspan` → mescla colunas.  

## 🔹 Boas Práticas Usadas
✔ Estrutura semântica com `<header>`, `<main>`, `<section>`, `<footer>`.  
✔ Uso de `<label>` para inputs (melhora acessibilidade).  
✔ Hierarquia correta de títulos (`h1`, `h2`).  
✔ Uso de `<abbr>`, `<figure>` e `<figcaption>` para dar significado ao conteúdo.  
✔ Separação clara entre conteúdo, formulários e feedback.  
✔ Tabela com `<thead>`, `<tbody>` e `<tfoot>` para melhor organização.  
✔ Links externos com `target="_blank"` para abrir em nova aba.  
