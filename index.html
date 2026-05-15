<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Valor Proporcional por Peso</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-image: url('fundo.png'); 
            background-size: cover; 
            background-position: center; 
            background-attachment: fixed;
        }
        label {
            display: block;
            margin-bottom: 8px;
        }
        input {
            padding: 8px;
            margin-bottom: 12px;
            width: 200px;
        }
        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        .resultado {
            margin-top: 20px;
            padding: 15px;
            background-color: rgba(0, 0, 0, 0.7); 
            color: white; 
            font-size: 18px; 
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            max-width: 400px; 
            margin: 20px auto; 
        }
        .resultado ol {
            padding-left: 20px; 
        }
        .resultado li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <h1 style="text-align:center">Calculadora de divisão de frete</h1>

    <label for="valor">Total do Frete</label>
    <input type="number" id="valor" placeholder="Digite o valor total do frete em R$" required>

    <label for="pesos">Pesos (separados por vírgula):</label>
    <input type="text" id="pesos" placeholder="Digite os pesos em kg" required>

    <button onclick="calcular()">Calcular</button>

    <div class="resultado" id="resultado"></div>

    <script>
        function calcular() {
            var valor = parseFloat(document.getElementById("valor").value);
            var pesos = document.getElementById("pesos").value.split(",").map(function(peso) {
                return parseFloat(peso.trim());
            });

            if (isNaN(valor) || pesos.some(isNaN) || pesos.includes(0)) {
                alert("Por favor, insira valores válidos para o valor e os pesos.");
                return;
            }

            // Soma total dos pesos
            var somaPesos = pesos.reduce(function(soma, peso) {
                return soma + peso;
            }, 0);

            var resultadoHTML = "<ol>"; // Alterado para <ol> para lista numerada
            pesos.forEach(function(peso) {
                // Calcula o valor proporcional para cada peso
                var valorProporcional = (peso / somaPesos) * valor;

                // Formatação com vírgula e ponto de milhar
                var valorFormatado = valorProporcional.toLocaleString('pt-BR', {
                    minimumFractionDigits: 2,
                    maximumFractionDigits: 2
                });

                resultadoHTML += "<li> " + " R$ " + valorFormatado + "</li>";
            });
            resultadoHTML += "</ol>";
            
            document.getElementById("resultado").innerHTML = resultadoHTML;
        }
    </script>

</body>
</html>
