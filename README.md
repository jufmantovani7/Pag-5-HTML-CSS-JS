# Pag-5-HTML-CSS-JS
pagina 5
<body>
    <style>
        body {
        background-color: #000
        }
        </style>

    <style>
        body {
            color:#FFFFFF

        }
        
    </style>
    <center>
       
        <p><h1>Bem vindo(a) á pagina do usuario. É um prazer te-lô como cliente</h1></p>
    <form>
        <script src="https://code.jquery.com/jquery-latest.min.js"></script>
    </head>
    <body>
      <form action="javascript:void(0);">
        <label>Escolha seu sexo</label>
        <input type="radio" name="sexo" id="feminino"><label>Feminino</label>
        <input type="radio" name="sexo" id="masculino"><label>Masculino</label>
        <input type="submit" id="button">
      </form>
    </body>
  
    <script>
     $('#button').click(function(){
        if($('#feminino').is(':checked')){
          alert("Você escolheu feminino");
        }else if($('#masculino').is(':checked')){
          alert('Você escolheu masculino');
        }else{
          alert('Você não escolheu');
        }
      });
    </script>
        <hr><br>
        <label for="email-example">Digite seu e-mail</label>
        <input type="email" id="email-example">
        <hr><br>
        <label for="password-example">Digite uma senha</label>
        <input type="password" id="password-example">
        <hr><br>
        <input type="button" value="Clique aqui">
        <p><button>botão do usuario(Próximo)</button></p>
        <hr><br>
    </center>
        </form>
    </body>
