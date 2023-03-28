# teste
index teste


<!DOCTYPE html>
<html>
  <head>
    <title>Aluguel de Motos</title>
    <style>
    	body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}

nav li {
  margin-left: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

section {
  margin: 50px;
}

h2 {
  margin-bottom: 20px;
}

form label {
  display: inline-block;
  width: 100px;
}

form input[type="text"] {
  width: 300px;
  padding: 5px;
  margin-bottom: 10px;
}

input[type="button"] {
  background-color: #333;
  color: #fff;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

select {
  padding: 5px;
  margin-bottom: 10px;
}

table {
  border-collapse: collapse;
  width: 100%;
  margin-top: 20px;
}

table th, table td {
  border: 1px solid #ddd;
  text-align: left;
  padding: 8px;
}

table th {
  background-color: #333;
  color: #fff;
}


    </style>
  </head>
  <body>
    <header>
      <h1>Aluguel de Motos</h1>
      <nav>
        <ul>
          <li><a href="#cadastro">Cadastro de Clientes</a></li>
          <li><a href="#multas">Multas</a></li>
        </ul>
      </nav>
    </header>

    <section id="cadastro">
      <h2>Cadastro de Clientes</h2>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome"><br>

        <label for="cpf">CPF:</label>
        <input type="text" id="cpf" name="cpf"><br>

        <label for="telefone">Telefone:</label>
        <input type="text" id="telefone" name="telefone"><br>

        <label for="endereco">Endereço:</label>
        <input type="text" id="endereco" name="endereco"><br>

        <input type="button" value="Cadastrar" onclick="cadastrarCliente()">
      </form>
    </section>

    <section id="multas">
      <h2>Multas</h2>
      <label for="clientes">Clientes:</label>
      <select id="clientes" onchange="consultarMultas()">
        <option value="">Selecione um cliente</option>
      </select>

      <div id="lista-multas"></div>
    </section>

    <script>
    	let clientes = [];

function cadastrarCliente() {
  let nome = document.getElementById("nome").value;
  let cpf = document.getElementById("cpf").value;
  let telefone = document.getElementById("telefone").value;
  let endereco = document


    </script>
  </body>
</html>
