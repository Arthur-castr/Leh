<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>De Arthur para Letícia</title>
    <link rel="apple-touch-icon" sizes="180x180" href="/arquivosdoprojeto/android-chrome-192x192.png">
    <link rel="icon" type="image/png" sizes="32x32" href="arquivosdoprojeto/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="arquivosdoprojeto/favicon-16x16.png">
    <link rel="manifest" href="arquivosdoprojeto/site.webmanifest">
  
   <style>
        @charset "UTF-8";
        @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

        :root{

            --cor0:#e0e7a3;
            
            --fonte-padrao: Arial,Verdana,Helvetica,sans-serif;
            --fonte-destaque:'Bebas Neue', sans-serif;
            --fonte-titulos:'Pacifico',sans-serif;
        

        }
        body{
            background-color: rgb(165, 119, 209);
        }

        header{
            margin: 0px;

            padding-top: 50px;

            

            text-align: center;
            

            min-width: 150px;

        }
        main{
            justify-content:center;
            
            
            background-color: white;
            

            box-shadow: 0px 0px 0px rgba(0, 0, 0, 0.404);

            padding:20px;
            border-radius: 10px;
            border-bottom-left-radius: 10px;
            border-bottom-right-radius: 10px;

            min-width: 280px;
            max-width: 800px;
            margin: auto;

            
        }
        img{
            text-align: center;
        }
        h1{
            font-family: var(--fonte-titulos);
            text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.418);
        }
        main h2{
            font-weight: normal;
            font-family:var(--fonte-titulos);
            background-image: linear-gradient(to right,var(--cor0),transparent);
            color: rgba(0, 0, 0, 0.644);
            margin: 0px;
            text-shadow: 2px 2px 0px rgba(87, 85, 85, 0.247);
        }
        p{
            font-family: var(--fonte-destaque);
            color:  rgb(165, 119, 209);
            text-shadow: 1px 1px 0px rgba(37, 37, 37, 0.274);
        }
        p#piada{
            color:#1b1b19;
            text-shadow: 1px 1px 0px rgba(0, 0, 0, 0.329);
            
        }
        p#mençao{
            color: rgba(129, 57, 197, 0.61);
        };
        img{
            width: 100%;
        }
        div#central{
            text-align: center;
        }



   </style>
</head>
<body>
    <form id="loginForm">
        <input type="password" id="passwordInput" placeholder="Digite a senha">
        <button type="button" onclick="checkPassword()">Entrar</button>
    </form>
    <div id="content" style="display: none;">
    <header>
        <h1>Bem vinda senhorita Sol</h1>
    </header>
    <main>
        <article>
            <h2>Espero que goste!</h2>
            <p>Leh,eu queria te dar algo em agradecimento aos momentos bons que estou passando ao seu lado, mas não sabia o que escolher. Então, decidi fazer isso em forma de uma página e tentei montar tudo aqui pensando em você!</p>
            <h2>Seu Sorriso</h2>
            <p>
                Desde que eu te conheci, vi de cara a pessoa simpática e agradável que você era. Mas foi só me aproximando que pude perceber o impacto que você causa nas pessoas, especialmente em mim.
            </p>
            <div id="central">
                <img src="arquivosdoprojeto/leh1_resized.jpeg" alt="Senhorita Leh" id="larg">
                <img src="arquivosdoprojeto/leh2_resized (1).jpeg" alt="gatinha" id="larg">
            </div>
            <p>
                Vou começar falando desse sorriso que me pega de jeito. Acabo me perdendo nele muito facilmente e acho que você sabe disso. Chega a ser maldade a forma como o seu sorriso tira minha atenção e me traz paz de certa forma.Eu poderia tentar falar mais ,porém é dificil de explicar e vou cabar me embolando
            </p>
            <p>
                Esse é um dos motivos egoístas de eu querer sempre te ver alegre! para que você não pare de sorrir!Acaba sendo impossivel ver o seu sorriso e não sorrir tbm!
            </p>
            <h2>Leh autora</h2>
            <p>Vamos falar da chata que é viciada em livros agora...</p>
            <div id="central">
                <img src="arquivosdoprojeto/lehautora01_resized.jpeg" alt="autora1">
                <img src="arquivosdoprojeto/lehautora02_resized.jpeg" alt="autora2">
            </div>
            <p>
                Assim que a gente entra na sua página, está escrito: "Autora de romances fofos, fantasia e pessoas traumatizadas." Ênfase em traumatizadas (brincadeira). Acho incrível o empenho e o amor que você tem pelos livros, e aposto que isso foi uma grande parte do que te ajudou a ser uma pessoa tão cheia de conteúdo! Ver sua paixão pelos livros está quase me fazendo tentar criar o hábito de ler também. Mesmo achando você um pouco louca às vezes, eu adoro essa Leh apaixonada por histórias. Os livros acabam sendo sua terapia, assim como o futebol é a minha, então eu admiro sua paixão porque de certa forma, eu entendo como é. 
            </p>
            <p id="piada">
                Dialogar na festa :não <br>
                ficar no kindle até a festa acabar: lógico!!
            </p>
            <p id="mençao">
                "Ler livros não é um ato é um sentimento"
            </p>
           <h2>Gentileza e Empatia</h2>
           <p>Sobre gentileza e empatia, eu poderia dizer que você é tipo um sinônimo dessas duas palavras.</p>
           <div id="central">
            <img src="arquivosdoprojeto/lehgentil_resized.jpeg" alt="gent1">
            <img src="arquivosdoprojeto/lehgentil2_resized.jpeg" alt="gent2">
           </div>
           <p>
             Me aproximando de você, vi o carinho que você tem com as pessoas. Sua gentileza fala muito alto, e sua empatia te torna diferente. Mesmo eu não concordando com certas atitudes suas, como ser gentil demais e as pessoas acabarem se aproveitando, eu nunca vou brigar com você por isso. Não é você que está fazendo o mal, e sim o mundo que trata pessoas incríveis de forma errada! Só lembre de ser gentil com você em primeiro lugar.
           </p>
           <p id="mençao">"A gentileza é o jeito mais bonito de ser o sol no dia nublado de alguem."</p>
           <h2>Momentos</h2>
           <p>Uma coisa que eu e você concordamos e que momentos são definidos mais pelas pessoas que nos rodeiam do que sobre o local em si! </p>
           <div id="central">
            <img src="arquivosdoprojeto/junina.jpeg" alt="dançando">
           </div>
           <p>Como não falar dessa festa junina? Foi aí que a gente conversou pela primeira vez de verdade. Esse dia foi muito bom e engraçado. Eu estava entre os meus amigos e consegui conhecer muita gente boa. Falei com você, e foi um dos maiores arrependimentos da minha vida! Se eu soubesse que ia arrumar uma companhia tão chata, voltava no tempo kkkkk. Brincadeiras à parte, esse dia me traz boas lembranças. Inclusive, para quem não gosta de dançar, esse sorriso na foto me diz outra coisa.</p>
           <div id="central">
            <img src="arquivosdoprojeto/vermelho_resized.jpeg" alt="vermelho">
           </div>
           <p>O time vermelho foi o melhor, disparado. A Naylla claramente doida, GB no grito, eu, Kauan e você no suporte (só maluco). A animação foi legal. Admito que sou bem competitivo, mas nesse caso eu não estava ligando muito. Porém, o time deu a vida e, mesmo perdendo naquele dia (roubado!!), a alegria da galera, especialmente a sua, foi boa de se ver.</p>
           <p>E falando em vermelho, lembrei da sua irmã dizendo que você era Vasco, mas você me mandou essa pérola aqui e me provou o contrário.
           </p>
           <audio controls>
            <source src="arquivosdoprojeto/audio1.ogg" type="audio/ogg">
        </audio>
           <div id="central">
            <img src="arquivosdoprojeto/encontro_resized.jpeg" alt="encontro">
           </div>
           <p>Eu poderia continuar falando sobre esses momentos, inclusive sobre o dia maravilhoso da foto de cima, mas estou mais preocupado com os próximos momentos que vão chegar. Não vou me aprofundar muito para não me expor...
           </p>
           <p>Espero que tenha gostado disso senhorita , do mesmo jeito que eu tenho gostado de passar o tempo com você.</p>
           <audio controls>
            <source src="arquivosdoprojeto/audio2.ogg" type="audio/ogg">
        </audio>
        </article>
    </main>
    </div>
    <script>
        function checkPassword() {
            const password = document.getElementById("passwordInput").value;
            if (password === "5384242") {
                document.getElementById("loginForm").style.display = "none";
                document.getElementById("content").style.display = "block";
            } else {
                alert("Senha incorreta. Tente novamente.");
            }
        }
    </script>
    
</body>
</html>
