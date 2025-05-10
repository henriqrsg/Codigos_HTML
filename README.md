# Codigos_HTML
Repositório dedicado a Arquivos feitos em HTML

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <title>Automatização Simples</title>
    <script>
        // Função que exibe uma mensagem após 3 segundos
        function mostrarMensagem() {
            alert("Processo automatizado concluído!");
        }

        // Executa a função após o carregamento da página
        window.onload = function() {
            setTimeout(mostrarMensagem, 3000); // 3000 milissegundos = 3 segundos
        };
    </script>
</head>
<body>
    <h1>Bem-vindo!</h1>
    <p>Este exemplo automatiza uma ação após alguns segundos.</p>
</body>
</html>
