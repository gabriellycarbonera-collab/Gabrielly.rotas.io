# Gabrielly.rotas.io
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema de Rotas de Transporte</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #eef3f7;
        }

        header {
            background: #1565C0;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            width: 95%;
            max-width: 1200px;
            margin: 20px auto;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        label {
            font-weight: bold;
            display: block;
            margin-top: 10px;
            margin-bottom: 5px;
        }

        input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            padding: 12px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 15px;
            margin-top: 15px;
        }

        .salvar {
            background: #2E7D32;
            color: white;
        }

        .editar {
            background: #FB8C00;
            color: white;
        }

        .excluir {
            background: #C62828;
            color: white;
        }

        .pesquisa {
            margin-bottom: 20px;
        }
        
