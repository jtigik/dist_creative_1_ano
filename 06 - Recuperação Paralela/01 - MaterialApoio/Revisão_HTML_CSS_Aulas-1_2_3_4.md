
### Roteiro de Aulas de Recuperação: Revisão de HTML e CSS

Este roteiro é projetado para alunos do segundo ano do ensino médio profissionalizante em Programador Web, com foco em revisão de conceitos básicos e intermediários de HTML e CSS. Como os alunos já trabalharam com HTML, CSS e Portugol, as aulas enfatizam a prática para reforçar o conhecimento, conectando conceitos de estrutura web com lógica de programação simples (sem introduzir novas linguagens). Cada aula tem 110 minutos (2 períodos de 55 minutos), divididos em: introdução/teoria (20-30 min), exemplos práticos (20-30 min) e exercícios com correção (40-50 min). Use um editor como VS Code ou um ambiente online como CodePen para as práticas. Incentive a colaboração em duplas para discussões.

#### Aula 1: Revisão Básica de HTML - Estrutura e Tags Essenciais (110 minutos)
**Objetivo:** Reforçar a estrutura básica de uma página HTML e tags comuns, conectando com conceitos de sequenciamento lógico (similar ao Portugol).

- **Período 1 (55 minutos): Introdução e Teoria (25 min) + Exemplos Práticos (30 min)**
  - **Introdução (25 min):** Comece com uma discussão rápida: "O que é HTML e por que é a base de uma página web? Lembrem-se: HTML é como o esqueleto de um site, definindo estrutura, enquanto CSS é a 'pele'." Revise a estrutura básica: `<!DOCTYPE html>`, `<html>`, `<head>` (com `<title>`, `<meta>`), `<body>`. Explique tags semânticas como `<header>`, `<main>`, `<footer>`, e tags básicas: `<h1>-<h6>`, `<p>`, `<ul>`, `<ol>`, `<li>`, `<a>`, `<img>`. Conecte com Portugol: "Assim como no Portugol usamos 'inicio' e 'fim' para blocos, HTML usa tags de abertura e fechamento."

  - **Exemplos Práticos (30 min):** Demonstre no projetor:
    - Exemplo 1: Crie uma página simples de "Meu Perfil".
      ```html
      <!DOCTYPE html>
      <html lang="pt-br">
      <head>
          <meta charset="UTF-8">
          <title>Meu Perfil</title>
      </head>
      <body>
          <header>
              <h1>Bem-vindo ao Meu Perfil</h1>
          </header>
          <main>
              <p>Olá, sou um aluno de Programador Web.</p>
              <ul>
                  <li>Idade: 16 anos</li>
                  <li>Hobbies: Programar e jogar</li>
              </ul>
              <a href="https://www.example.com">Visite meu site</a>
              <img src="imagem.jpg" alt="Foto de perfil" width="200">
          </main>
          <footer>
              <p>Copyright 2025</p>
          </footer>
      </body>
      </html>
      ```
      Explique: "Veja como as tags aninhadas criam hierarquia, como em laços no Portugol."

- **Período 2 (55 minutos): Exercícios e Correção (55 min)**
  - **Exercícios (35 min):** Os alunos trabalham individualmente ou em duplas.
    - Exercício 1: Crie uma página HTML básica para uma "Lista de Compras" com cabeçalho, parágrafo introdutório, lista não ordenada de itens e uma imagem de um carrinho (use placeholder como `src="carrinho.jpg"`).
    - Exercício 2: Adicione links: Um link para "Voltar à Home" e outro para um site externo (ex: Google). Teste no navegador.
  - **Correção e Discussão (20 min):** Circule pela sala, corrija erros comuns (ex: tags não fechadas). Peça que 2-3 alunos compartilhem suas páginas e expliquem uma tag usada, reforçando o conceito.

#### Aula 2: Revisão de HTML Avançado - Formulários e Tabelas (110 minutos)
**Objetivo:** Revisar elementos interativos como formulários e tabelas, enfatizando organização de dados (paralelo a arrays ou estruturas no Portugol).

- **Período 1 (55 minutos): Introdução e Teoria (25 min) + Exemplos Práticos (30 min)**
  - **Introdução (25 min):** Discuta: "HTML não é só texto; permite interação com formulários e organização com tabelas." Revise tags de tabela: `<table>`, `<tr>`, `<th>`, `<td>`. Para formulários: `<form>`, `<input>` (tipos: text, email, password, radio, checkbox), `<label>`, `<button>`, `<select>`. Mencione atributos como `action`, `method`, mas foque em estrutura (sem backend).
  - **Exemplos Práticos (30 min):** Demonstre:
    - Exemplo 1: Tabela de "Notas de Alunos".
      ```html
      <table border="1">
          <tr>
              <th>Aluno</th>
              <th>Nota HTML</th>
              <th>Nota CSS</th>
          </tr>
          <tr>
              <td>João</td>
              <td>8</td>
              <td>7</td>
          </tr>
          <tr>
              <td>Maria</td>
              <td>9</td>
              <td>10</td>
          </tr>
      </table>
      ```
    - Exemplo 2: Formulário simples de "Cadastro".
      ```html
      <form action="/enviar" method="post">
          <label for="nome">Nome:</label>
          <input type="text" id="nome" name="nome"><br>
          <label for="email">Email:</label>
          <input type="email" id="email" name="email"><br>
          <input type="radio" id="masculino" name="genero" value="masculino">
          <label for="masculino">Masculino</label>
          <input type="radio" id="feminino" name="genero" value="feminino">
          <label for="feminino">Feminino</label><br>
          <button type="submit">Enviar</button>
      </form>
      ```
      Conecte: "Como no Portugol usamos variáveis para armazenar dados, aqui inputs capturam informações."

- **Período 2 (55 minutos): Exercícios e Correção (55 min)**
  - **Exercícios (35 min):**
    - Exercício 1: Crie uma tabela para "Horário Escolar" com 3 colunas (Dia, Matéria, Horário) e pelo menos 4 linhas.
    - Exercício 2: Construa um formulário de "Enquete" com checkboxes para hobbies (ex: Esportes, Jogos, Leitura), um select para idade (opções: 14-16, 17-19) e um botão de submit.
  - **Correção e Discussão (20 min):** Verifique acessibilidade (ex: labels corretos). Discuta erros como colspan/rowspan se aplicável, e peça exemplos de como integrar com lógica (ex: "Se fosse Portugol, como validar um input?").

#### Aula 3: Revisão Básica de CSS - Seletores e Propriedades (110 minutos)
**Objetivo:** Reforçar estilização básica, ligando a seletores como condicionais no Portugol.

- **Período 1 (55 minutos): Introdução e Teoria (25 min) + Exemplos Práticos (30 min)**
  - **Introdução (25 min):** Explique: "CSS dá vida ao HTML, como estilos em um programa." Revise inclusão de CSS: inline, internal (`<style>`) ou external (`<link>`). Cobrir seletores: tag (ex: `p`), class (`.classe`), ID (`#id`). Propriedades básicas: `color`, `background-color`, `font-size`, `margin`, `padding`, `border`.
  - **Exemplos Práticos (30 min):** Use o HTML da Aula 1 e adicione CSS.
    - Exemplo 1: Estilo básico (internal).
      ```html
      <style>
          body { background-color: #f0f0f0; font-family: Arial; }
          h1 { color: blue; text-align: center; }
          .destaque { font-weight: bold; color: red; }
      </style>
      <!-- No body: <p class="destaque">Texto em destaque</p> -->
      ```
    - Exemplo 2: External CSS (crie arquivo style.css e linke).
      ```css
      a { text-decoration: none; color: green; }
      a:hover { color: orange; }
      ```

- **Período 2 (55 minutos): Exercícios e Correção (55 min)**
  - **Exercícios (35 min):**
    - Exercício 1: Pegue a página da Aula 1 e adicione CSS para centralizar o cabeçalho, mudar cor de fundo e estilizar links.
    - Exercício 2: Crie classes para itens de lista (ex: .item-vermelho) e aplique em uma ul.
  - **Correção e Discussão (20 min):** Foque em especificidade de seletores. Relacione com Portugol: "Seletores são como 'se' para aplicar estilos condicionais."

#### Aula 4: Revisão de CSS Avançado - Layouts e Responsividade (110 minutos)
**Objetivo:** Revisar layouts flexíveis, preparando para designs modernos.

- **Período 1 (55 minutos): Introdução e Teoria (25 min) + Exemplos Práticos (30 min)**
  - **Introdução (25 min):** Discuta: "CSS avançado permite layouts dinâmicos." Revise display: block/inline/flex, flexbox (`display: flex;`, `justify-content`, `align-items`). Introduza media queries para responsividade.
  - **Exemplos Práticos (30 min):**
    - Exemplo 1: Flexbox para menu.
      ```css
      .container { display: flex; justify-content: space-around; }
      .item { padding: 10px; border: 1px solid black; }
      ```
      HTML: `<div class="container"><div class="item">Item 1</div>...</div>`
    - Exemplo 2: Media query.
      ```css
      @media (max-width: 600px) { body { font-size: 14px; } }
      ```

- **Período 2 (55 minutos): Exercícios e Correção (55 min)**
  - **Exercícios (35 min):**
    - Exercício 1: Aplique flexbox a uma seção de cards (3 itens lado a lado) em uma página HTML.
    - Exercício 2: Adicione media query para mudar layout em telas pequenas (ex: stack vertical).
  - **Correção e Discussão (20 min):** Teste em diferentes tamanhos de tela. Encerrar com visão geral: "Como no Portugol, CSS usa lógica para adaptações."