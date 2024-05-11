<!DOCTYPEhtml>
<!--
Tutorial: https://www.youtube.com/watch?v=zxxB9SFh9p4
-->
<html lang="pt">

<cabeça>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="largura=largura do dispositivo, escala inicial=1,0">
    <title>pedidoDeDesculpas.com</title>
</head>

<corpo>
    <div id="conteudo">
        <h2>princesa linda, aceita namorar comigo?</h2>
        <div style="margem: auto;largura: 170px;">
            <button style="posição: fixa;exibição: bloco;" class="btn" onclick="sim()">SIM</button>
            <button class="btn" onclick="desvia(this)" onmouseover="desvia(this)" style="position: absoluto;">NÃO</button>
        </div>
    </div>
</body>
<estilo>
    #conteudo {
        plano de fundo: #6e3661;
        largura: 100%;
        altura: 100%;
        posição: fixa;
        superior: 0;
        esquerda: 0;
        preenchimento: 10px;
        alinhamento de texto: centro;
        família de fontes: sem serifa;
    }

    .btn {
        fundo: preto;
        cor branca;
        fronteira: nenhuma;
        preenchimento: 10px;
        largura: 80px;
        raio da borda: 5px;
    }
</estilo>

<roteiro>
    função sim() {
        alert("Você aceitou sair comigo :D");
        // redireciona para um URL após clicar no SIM
        location.href = "https://www.youtube.com/watch?v=izGwDsrQ1eQ&ab_channel=georgemichaelVEVO";
    }

    function desvia(btn) {
        // btn declarado na função
        btn.style.position = 'absoluto';
        btn.style.bottom = geraPosicao(10, 90);
        btn.style.left = geraPosicao(10, 90);
        console.log('opa, desviei...');
    }

    function geraPosicação(min, max) {
        return (Math.random() * (máx - min) + min) + "%";
    }

</script>

</html>
--->
