<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela de Estudantes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            width: 80%;
            background: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.1);
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header a {
            color: #ff9800;
            text-decoration: none;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #444;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #ff9800;
            color: black;
        }
        tr:nth-child(even) {
            background-color: #222;
        }
        .form-container {
            margin-top: 30px;
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        input, select, button {
            padding: 12px;
            border-radius: 5px;
            border: 1px solid #666;
            background-color: #333;
            color: white;
        }
        button {
            background-color: #ff5722;
            cursor: pointer;
        }
        button:hover {
            background-color: #e64a19;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h2>Tabela de Estudantes</h2>
            <a href="T.2.html">TPC T.2</a>
        </div>
        <table>
            <tr>
                <th>ID</th>
                <th>Nome</th>
                <th>Idade</th>
                <th>Turma</th>
                <th>Email</th>
                <th>Telefone</th>
                <th>Nota Final</th>
                <th>Situação</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Fredy Mucoco</td>
                <td>22</td>
                <td>BNI</td>
                <td>mucoco111@gmail.com</td>
                <td>929724711</td>
                <td>19</td>
                <td>Aprovado</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Simone Zua</td>
                <td>22</td>
                <td>BNI</td>
                <td>simonesimonezua@yahoo.com</td>
                <td>923456789</td>
                <td>19</td>
                <td>Aprovado</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Alexandre Adula</td>
                <td>20</td>
                <td>BNI</td>
                <td>Alexandreadula@email.com</td>
                <td>923123456</td>
                <td>19</td>
                <td>Aprovado</td>
            </tr>
        </table>

        <div class="form-container">
            <h3>Adicionar Estudante</h3>
            <form>
                <input type="text" placeholder="Digite o ID">
                <input type="text" placeholder="Digite o Nome">
                <input type="number" placeholder="Digite a Idade">
                <input type="text" placeholder="Digite a Turma">
                <input type="email" placeholder="Digite o Email">
                <input type="tel" placeholder="Digite o Telefone">
                <input type="number" step="0.1" placeholder="Digite a Nota">
                <select>
                    <option value="Aprovado">Aprovado</option>
                    <option value="Reprovado">Reprovado</option>
                </select>
                <button type="submit">Adicionar Estudante</button>
            </form>
        </div>
    </div>
</body>
</html>
