<html>
<head>

    <meta charset="UTF-8">

    <title>projeto</title>
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
        Prometo que vou te fazer feliz e tudo que estiver ao meu alcance, você é a pessoa mais importante da minha vida e sempre vai ser.");
        }

        
        function fPreto(){
            alert("Quero um amor sossegado. Alguém para me abraçar\n\
        assistir um filme, jogar baralho, viajar, conversar, contar o dia, fazer cafuné, dar apoio, conforto. Quero troca, carinho, respeito, cumplicidade.\n\
        O amor é uma amizade sem inveja. É um sonho com realidade. É uma realidade sem photoshop. O amor é uma conversa boa, um abraço apertado, um olhar que se encontra.\n\
        Um silêncio que não incomoda, um barulho de onda, uma risada gostosa, um gosto bom. Não tem serenata, mas tem carta enviada. E rotina, cansaço, discussão, brigas, algumas discordancias de opinião.\n\
        Mas, acima de tudo, tem paciência, respeito, reciprocidade e muito amor. E muita vontade para que dê o mais certo possível pro resto da vida.");
        }

        function fRoxo(){
            alert("Você sabe que além de eu gostar muito de você, quero que você faça parte da minha vida, quero sua companhia, quero você me acompanhando.\n\
        Quero que você esteja comigo pra tudo nessa vida, partes boas, risadas, sonhos, alegrias, partes ruins, vou estar sempre ao seu lado pro que der e vier.\n\
        Eu realmente te amo e é muito! Meu pensamento é todo em você.");
        }


        function fVermelho(){
            alert("Hoje 10 de Setembro, seu dia 10, número escolhido por você e o que deu certo meu mês. Já está sendo perfeito de novo para fazer o meu pedido... Lo-Ami Moreira Quer namorar comigo?");
        }
        function confirmar(){
            var varConfirm = document.getElementById('texto').value;
            if(varConfirm ==''){
            alert('Parabéns! Certa resposta.');
            }
        }

        function confirm(){
            var varConfirm = document.getElementById('texto').value;
            if(varConfirm ==''){
            alert('Erro! Não tem essa resposta hahaha.');
            }
        }
        function mOver(obj) {
            obj.innerHTML = "Te Amo Muito!! Minha linda pra sempre!"
        }

        function mOut(obj) {
            obj.innerHTML = "Passa o mouse em cima"
        }

        function myMove() {
            var elem = document.getElementById("animate");   
            var pos = 0;
            var id = setInterval(frame, 5);
            alert("Só para finalizar, você fez uma ótima escolha, eu e você para sempre! :D");
        function frame() {
             if (pos == 350) {
                clearInterval(id);
        } else {
            pos++; 
            elem.style.top = pos + 'px'; 
            elem.style.left = pos + 'px'; 
        
        }
        }
        }   

          
    </script>

    <style>

        body{
            background:linear-gradient(to right, #004f99, rgb(102, 179, 255));
        }
        h1{
            font-size: 20px;
        }
        #azul{
            background-color: blue;
            width: 100px;
            height: 100px;
            margin: 100px auto;
            border-radius: 15px;
        }
        #laranja{
            background-color: orange;
            width: 100px;
            height: 100px;
            margin: 20px auto;
            border-radius: 15px;
        }
        #amarelo{
            background-color: yellow;
            width: 100px;
            height: 100px;
            margin: 20px auto;
            border-radius: 15px;
        }
        #container {
            width: 400px;
            height: 400px;
            position: relative;
            background: grey;
            border-radius: 15px;
        }
        #animate {
            width: 50px;
            height: 50px;
            position: absolute;
            background-color: green;
            border-radius: 15px;
        }
        #preto{
            background-color: black;
            width: 100px;
            height: 100px;
            margin: 20px auto;
            border-radius: 15px;
        }
        #roxo{
            background-color: rebeccapurple;
            width: 100px;
            height: 100px;
            margin: 20px auto;
            border-radius: 15px;
        }
        .heart{
            background-color: red;
            width: 200px;
            height: 200px;
            margin: 200px auto;
            transform: rotate(-45deg);
            position: relative;
            cursor: pointer;
           
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
        button{
            font-size: 20px;
            padding: 10px 15px;
            border: 0;
            border-radius: 15px;
            color: white;
            font-family: 100;
            background: linear-gradient(to right, gold, rgb(255, 123, 0));
            cursor: pointer;
            margin-left: 100px;
            
        }

        button:hover{
            animation-name:botao;
            animation-duration:0.5s;
            animation-iteration-count: infinite;
            animation-direction: alternate;
            animation-timing-function: ease-in-out;
            box-shadow: 0 0 50px 20px rgba(255, 166, 0 , 0.5);

        }

        @keyframes botao{
            0%{
                transform: scale(1);
            }
            100%{
                transform: scale(1.05);
            }
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

    
    <div onmouseover="mOver(this)" onmouseout="mOut(this)" 
    style="background-color:#D94A38;width:120px;height:120px;padding:40px;">
    Passa o mouse em cima</div>

    <p>
        <button onclick="myMove()">Click Me</button>
        </p> 
        
        <div id ="container">
        <div id ="animate"></div>
        </div>
    

</body>
</html>
