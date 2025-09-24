
Três exercícios práticos para fixação de conteúdo sobre HTML e CSS, voltados para alunos em Recuperação. Os exercícios são baseados na página web fornecida anteriormente e possuem três níveis de dificuldade: **very easy**, **easy** e **medium**. Cada exercício inclui uma descrição, instruções claras e o objetivo de aprendizado.

---

### Exercício 1: Very Easy - Adicionando um Novo Item à Lista
**Objetivo**: Praticar a adição de conteúdo com a tag `<li>` e entender a estrutura de uma lista não ordenada.

**Descrição**: Os alunos irão modificar a lista na seção "Principais Tags HTML Utilizadas" da página HTML fornecida, adicionando um novo item que descreve a tag `<header>`.

**Instruções**:
1. Abra o arquivo `index.html` em um editor de texto (como Notepad++ ou VS Code).
2. Localize a seção com a lista `<ul>` dentro do primeiro `<section>`.
3. Adicione um novo item à lista usando a tag `<li>` com o seguinte texto: `<strong>&lt;header&gt;</strong>: Define o cabeçalho da página ou de uma seção.`
4. Salve o arquivo e abra-o no navegador para verificar o resultado.

**Dica**: Certifique-se de que o novo `<li>` esteja dentro do `<ul>` e siga o mesmo formato dos outros itens.

**Resultado Esperado**: A lista na página agora terá um item adicional descrevendo a tag `<header>`.

**Habilidade Praticada**: Manipulação de tags HTML básicas (`<ul>`, `<li>`, `<strong>`).

---

### Exercício 2: Easy - Alterando Estilos no CSS
**Objetivo**: Praticar a edição de propriedades CSS e entender como elas afetam elementos HTML.

**Descrição**: Os alunos irão modificar o arquivo `styles.css` para mudar a cor do texto dos cabeçalhos `<h2>` e o fundo do corpo (`body`) da página.

**Instruções**:
1. Abra o arquivo `styles.css` em um editor de texto.
2. Localize a regra para o elemento `h2` (está dentro de `h1, h2`).
3. Altere a cor dos cabeçalhos `<h2>` para roxo (`purple`) adicionando uma regra específica: `h2 { color: purple; }`.
4. Mude a cor de fundo do `body` para um cinza claro (`#e0e0e0`).
5. Salve o arquivo e recarregue a página no navegador para verificar as mudanças.

**Dica**: Certifique-se de que a nova regra para `h2` não interfira com a cor do `h1`. Você pode adicionar a regra `h2` abaixo da regra combinada `h1, h2`.

**Resultado Esperado**: Os cabeçalhos `<h2>` aparecerão em roxo, e o fundo da página estará em cinza claro.

**Habilidade Praticada**: Edição de propriedades CSS (`color`, `background-color`) e compreensão da especificidade de seletores.

---

### Exercício 3: Medium - Criando uma Nova Seção com Link e Estilo
**Objetivo**: Combinar HTML e CSS para criar uma nova seção com conteúdo interativo e aplicar estilos personalizados.

**Descrição**: Os alunos irão adicionar uma nova seção à página HTML com um título, um parágrafo e um link para um site de aprendizado (como o MDN Web Docs). No CSS, eles criarão estilos para destacar essa nova seção.

**Instruções**:
1. Abra o arquivo `index.html` em um editor de texto.
2. Antes do `<footer>`, adicione uma nova seção com o seguinte conteúdo:
   ```html
   <section>
       <h2>Recursos Adicionais</h2>
       <p>Explore mais sobre HTML e CSS com este recurso:</p>
       <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML" target="_blank">MDN Web Docs - HTML</a>
   </section>
   ```
3. Abra o arquivo `styles.css` e adicione uma regra para estilizar a nova seção:
   ```css
   section:nth-child(3) {
       background-color: #d4edda;
       padding: 15px;
       border-radius: 5px;
       margin-top: 20px;
   }
   ```
4. Salve ambos os arquivos e recarregue a página no navegador para verificar o resultado.

**Dica**: A propriedade `section:nth-child(3)` seleciona a terceira seção dentro do `<main>`. Certifique-se de que a nova seção está corretamente posicionada no HTML.

**Resultado Esperado**: A página agora terá uma nova seção com um título, um parágrafo e um link funcional. A seção terá um fundo verde claro, bordas arredondadas e espaçamento interno.

**Habilidade Praticada**: Criação de novos elementos HTML (`<section>`, `<h2>`, `<p>`, `<a>`), aplicação de estilos CSS avançados (`background-color`, `padding`, `border-radius`, `margin`) e uso de seletores específicos (`nth-child`).

---

**Notas para o Professor**:
- **Very Easy**: Ideal para alunos que estão começando a entender a estrutura do HTML. Foca em copiar e colar com pequenas modificações.
- **Easy**: Introduz edição de CSS, permitindo que os alunos vejam mudanças visuais imediatas sem alterar a estrutura do HTML.
- **Medium**: Combina HTML e CSS, exigindo maior compreensão da relação entre os dois arquivos e introduzindo seletores mais avançados.
- Os alunos podem testar as alterações em navegadores e compartilhar os resultados com o grupo para discussão.
- Para verificar os resultados, peça que os alunos abram os arquivos no navegador após cada modificação e discutam o impacto das mudanças.