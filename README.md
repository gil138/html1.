<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exemplo Completo de HTML - Módulos 1 a 3</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 30px;
      background-color: #f8f8f8;
      color: #333;
    }

    header, footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 15px;
      border-radius: 8px;
    }

    section {
      background-color: white;
      margin: 20px 0;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }

    h1, h2 {
      color: #004080;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: left;
    }

    th {
      background-color: #e0e0e0;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 400px;
    }

    input, textarea, select, button {
      padding: 8px;
      border-radius: 5px;
      border: 1px solid #aaa;
    }

    button {
      background-color: #004080;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #0066cc;
    }
  </style>
</head>

<body>
  <header>
    <h1>Desenvolvimento Web I – Front-End</h1>
    <p>Prof. Peterson Lobato</p>
  </header>

  <section>
    <h2>1️⃣ Introdução ao HTML</h2>
    <p>
      HTML (HyperText Markup Language) é a linguagem usada para estruturar o conteúdo da web.
      Ele utiliza <strong>tags</strong> para indicar a função de cada parte do conteúdo, como
      <code>&lt;h1&gt;</code> para títulos e <code>&lt;p&gt;</code> para parágrafos.
    </p>

    <h3>Exemplo básico:</h3>
    <h1>Desenvolvimento WEB</h1>
    <p>Estou estudando desenvolvimento web – front-end, através do desenvolvimento de jogos.</p>

    <p><em>HTML estrutura o conteúdo, CSS cuida do visual e JavaScript adiciona interatividade.</em></p>
  </section>

  <section>
    <h2>2️⃣ Estrutura e Sintaxe</h2>
    <p>Todo documento HTML segue uma estrutura hierárquica bem definida:</p>

    <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="pt-BR"&gt;
  &lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Minha primeira página&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Olá, Web!&lt;/h1&gt;
    &lt;p&gt;Esta é minha primeira página.&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
    </pre>

    <h3>Exemplo de elementos inline e de bloco:</h3>
    <p>Este texto tem uma <strong>palavra em destaque</strong> e um <a href="#">link</a>.</p>
  </section>

  <section>
    <h2>3️⃣ Listas</h2>

    <h3>Lista não ordenada:</h3>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ul>

    <h3>Lista ordenada:</h3>
    <ol>
      <li>Planejar</li>
      <li>Desenvolver</li>
      <li>Publicar</li>
    </ol>

    <h3>Lista de definição:</h3>
    <dl>
      <dt>HTML</dt>
      <dd>Linguagem de marcação usada na web.</dd>
    </dl>
  </section>

  <section>
    <h2>4️⃣ Tabelas</h2>
    <table>
      <thead>
        <tr>
          <th>Produto</th>
          <th>Preço</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Notebook</td>
          <td>R$ 3.500,00</td>
        </tr>
        <tr>
          <td>Mouse</td>
          <td>R$ 50,00</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td colspan="2">Dados de 2025</td>
        </tr>
      </tfoot>
    </table>
  </section>

  <section>
    <h2>5️⃣ Formulário</h2>
    <form action="processa.php" method="post">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>

      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" placeholder="Digite seu e-mail" required>

      <label for="cidade">Cidade:</label>
      <select id="cidade" name="cidade">
        <option value="">Selecione...</option>
        <option value="sp">São Paulo</option>
        <option value="rj">Rio de Janeiro</option>
        <option value="ba">Bahia</option>
      </select>

      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" rows="4" cols="30"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 - Exemplo educacional baseado nos módulos 1 a 3 de HTML</p>
  </footer>
</body>
</html>
