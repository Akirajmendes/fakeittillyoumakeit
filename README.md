
# Alura-Akira
<meta charset="UTF-8">
<script>
    function pulaLinha() {
        document.write("<br>");
    }

    function mostra(frase) {
        document.write(frase);
    }

    var minhaIdade = 18;
    var idadeIrmao = 15;

    mostra("Nossa diferença de idade é " + (minhaIdade - idadeIrmao));
    pulaLinha();
</script>
<meta charset="UTF-8">

    <script>
        function pulaLinha() {
            document.write("<br>");
        }

        function mostra(frase) {
            document.write(frase);
            pulaLinha();
        }

        var idadeMediaQuandoTemFilhos = 28;
        var anoAtual = 2016; 

        var quantidadeDeGeracoes = (anoAtual - 1500) / idadeMediaQuandoTemFilhos;

        mostra(quantidadeDeGeracoes);
    </script>
