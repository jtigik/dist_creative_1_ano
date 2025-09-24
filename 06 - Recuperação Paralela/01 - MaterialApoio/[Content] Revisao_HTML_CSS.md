```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo Básico de Página Web</title>
    <!-- Referenciando o arquivo de estilos CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo à Página de Aprendizagem em Programação Web</h1>
        <p>Esta página é um exemplo simples para reforçar os conceitos básicos de HTML e CSS.</p>
    </header>

    <main>
        <section>
            <h2>Principais Tags HTML Utilizadas</h2>
            <ul>
                <li><strong>&lt;!DOCTYPE html&gt;</strong>: Declara o tipo de documento como HTML5.</li>
                <li><strong>&lt;html&gt;</strong>: Elemento raiz da página.</li>
                <li><strong>&lt;head&gt;</strong>: Contém metadados, como título e links para estilos.</li>
                <li><strong>&lt;title&gt;</strong>: Define o título da página exibido na aba do navegador.</li>
                <li><strong>&lt;link&gt;</strong>: Usado para referenciar o arquivo CSS externo.</li>
                <li><strong>&lt;body&gt;</strong>: Contém o conteúdo visível da página.</li>
                <li><strong>&lt;h1&gt;, &lt;h2&gt;</strong>: Cabeçalhos de diferentes níveis.</li>
                <li><strong>&lt;p&gt;</strong>: Parágrafos de texto.</li>
                <li><strong>&lt;ul&gt;, &lt;li&gt;</strong>: Lista não ordenada e itens de lista.</li>
                <li><strong>&lt;a&gt;</strong>: Links para outras páginas ou sites.</li>
                <li><strong>&lt;img&gt;</strong>: Insere imagens na página.</li>
            </ul>
        </section>

        <section>
            <h2>Exemplo de Link e Imagem</h2>
            <p>Clique no link abaixo para acessar um recurso útil:</p>
            <a href="https://www.w3schools.com/html/" target="_blank">Tutorial de HTML no W3Schools</a>
            <p>Aqui está uma imagem ilustrativa:</p>
            <img src="https://via.placeholder.com/300x200" alt="Imagem de placeholder para exemplo">
        </section>
    </main>

    <footer>
        <p>&copy; 2025 - Exemplo para Alunos de Ensino Médio Profissionalizante.</p>
    </footer>
</body>
</html>
```

```css
/* styles.css */
/* Estilos básicos para melhorar a aparência da página */

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 20px;
    line-height: 1.6;
}

header {
    text-align: center;
    margin-bottom: 20px;
}

h1, h2 {
    color: #007BFF;
}

ul {
    list-style-type: disc;
    padding-left: 20px;
}

a {
    color: #28a745;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 10px auto;
}

footer {
    text-align: center;
    margin-top: 30px;
    font-size: 0.9em;
    color: #666;
}
```

Para usar esses arquivos, crie dois arquivos separados: um chamado `index.html` com o conteúdo HTML acima e outro chamado `styles.css` com o conteúdo CSS. Coloque-os na mesma pasta. Ao abrir o `index.html` em um navegador, a página será exibida com os estilos aplicados. Isso serve como material de reforço para os alunos, demonstrando tags HTML principais e como referenciar um CSS externo. Eles podem editar e experimentar para aprender mais.