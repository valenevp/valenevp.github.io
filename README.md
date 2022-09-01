<!doctype html>
<html>
<head>

    <meta charset="UTF-8">

    <title>alert</title>
    <script type="text/javascript">

        function fTeclado(){
        alert("Clique no Sim ou Não");
        }

        function fAzul(){
            alert("Azul cor do céu , cor do mar, calmaria e tempestade, já é a cor preferida de nós duas, então vai ser o ínicio de tudo.\n\
        Isso já é outro sinal pra dar certo nessa vida! Segue para próxima cor...");
        }

        function fLaranja(){
            alert("Eu não acreditava em destino, eu procuro e você está ao meu lado.\n\
        Eu sou seu, e de repente você é minha! Isso é só um trecho da nossa música entre tantas musicas que me lembra você!");
        }

        function fAmarelo(){
            alert("Eu sei que fiz algumas coisas erradas, mas estou aqui querendo te mandar um recado!\n\
        Prometo que vou te fazer feliz e tudo que estiver ao meu alcance, você é a pessoa mais importante da minha vida.");
        }

        
        function fVerde(){
            alert("")
        }

        function fPreto(){
            alert("")
        }

        function fRoxo(){
            alert("Quero um amor sossegado. Alguém para me abraçar\n\
        assistir um filme, jogar baralho, viajar, conversar, contar o dia, fazer cafuné, dar apoio, conforto. Quero troca, carinho, respeito, cumplicidade.\n\
        O amor é uma amizade sem inveja. É um sonho com realidade. É uma realidade sem photoshop. O amor é uma conversa boa, um abraço apertado, um olhar que se encontra.\n\
        Um silêncio que não incomoda, um barulho de onda, uma risada gostosa, um gosto bom. Não tem serenata, mas tem carta enviada. E rotina cansaço, discussão, brigas, algumas discordancias de opnião.\n\
        Mas, acima de tudo, tem paciência, respeito, reciprocidade e muito amor. E muita vontade para que dê o mais certo possível pro resto da vida");
        }


        function fVermelho(){
            alert("Hoje 10 de Setembro, seu dia 10, número escolhido por você e o que deu certo meu mês, Já está sendo perfeito de novo para fazer o meu pedido... Lo-Ami Moreira Quer namorar comigo?");
        }
        function confirmar(){
            var varConfirm = document.getElementById('texto').value;
            if(varConfirm ==''){
            alert('Certa resposta.');
            }
            }
        function confirm(){
            var varConfirm = document.getElementById('texto').value;
            if(varConfirm ==''){
            alert('Não tem essa resposta hahaha.');
            }
        }

            
    </script>

    <style>

        body{
            background-color:#99ccff;
        }
        h1{
            font-size: 20px;
        }
        #azul{
            background-color: blue;
            width: 100px;
            height: 100px;
            margin: 100px auto;
        }
        #laranja{
            background-color: orange;
            width: 100px;
            height: 100px;
            margin: 20px auto;
        }
        #amarelo{
            background-color: yellow;
            width: 100px;
            height: 100px;
            margin: 20px auto;
        }
        #verde{
            background-color: green;
            width: 100px;
            height: 100px;
            margin: 20px auto;
        }
        #preto{
            background-color: black;
            width: 100px;
            height: 100px;
            margin: 20px auto;
        }
        #roxo{
            background-color: rebeccapurple;
            width: 100px;
            height: 100px;
            margin: 20px auto;
        }
        .heart{
            background-color: red;
            width: 200px;
            height: 200px;
            margin: 200px auto;
            transform: rotate(-45deg);
            position: relative;
        }
        .heart:before,
        .heart:after{
            content:"";
            background-color: red;
            border-radius:50%;
            width: 200px;
            height: 200px;
            position: absolute;
        }
        .heart:before{
            top: -100px;
        }
        .heart:after{
            left:100px;
        }
              


    </style>
</head>
    
    <h1>Olá Lo-Ami para dar início ao projeto que te preparei é simples. 
        Segue as instruções, clicar 1º na cor Azul e assim por diante, ao chegar no vermelho, você tem que clicar no que quer embaixo: 
        Aproveite e espero que goste!</h1>

<body onkeypress="fTeclado()">
    <div id="azul" onclick='fAzul()'></div>
    <div id="laranja" onclick='fLaranja()'></div>
    <div id="amarelo" onclick='fAmarelo()'></div>
    <div id="verde" onclick='fVerde()'></div>
    <div id="preto" onclick='fPreto()'></div>
    <div id="roxo" onclick='fRoxo()'></div>
    <div class="heart" onclick='fVermelho()'></div>


    <textarea id="texto"></textarea>
    <input type="submit" value="Sim" onclick="confirmar()"> 
    <input type="submit" value="Não" onclick="confirm()">


   

</body>
</html>
