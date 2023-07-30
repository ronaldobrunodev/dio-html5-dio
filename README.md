# dio-html5-formulario
Formulário em HTML 5, do projeto DIO

Estrutura em HTML 5
<!DOCTYPE html>
<html lang="pt_br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Projeto DIO</title>
</head>
<body>
   <h2>FORMULÁRIO</h2>
   <fieldset>
        <legend>Dados Pessoas </legend>
        <div class="row">
            <label>Nome: </label> <input type="text" name="Nome" id="nome" placeholder="Digite seu nome"/>
            <label>E-mail</label> <input type="email" name="E-mail" id="e-mail" placeholder="email@email.com"/>
        </div>
        <div class="row">
            <label>Profissão: </label> <input type="text" name="Profissao" id="profissao" placeholder="Digite sua profissão"/>
            <label>Empresa</label> <input type="text" name="Empresa" id="empresa" placeholder="Digite o nome da empresa"/>
        </div>
   </fieldset>

   <fieldset>
    <legend>Endereço</legend>
    <div class="row">
        <label>Endereço: </label> <input type="text" name="Endereço" id="endereço" placeholder="Digite o nome da sua rua"/>
        <label>Apartamento</label> <input style="width: 40px; text-align: center" width="10"  type="text" name="Apartamento" id="ap" placeholder="2B" max="5"/>
        <label>Número</label> <input style="width: 40px; text-align: center" width="10"  type="number" name="Número" id="numero" placeholder="123" max="5"/>

           
    </div>
    <div class="row">
        <label>Bairro</label> <input type="text" name="Bairro" id="bairro" placeholder="Digite o nome do bairro"/>   
        <label>Referencia</label> <input type="text" name="Bairro" id="bairro" placeholder="Digite o ponto de referência"/>       
    </div>
    <div class="row">
        <label>Cidade: </label> <input type="text" name="Cidade" id="cidade" placeholder="Digite sua cidade"/>
        <label>Estado: </label> <input type="text" name="UF" id="profissao" placeholder="Digite seu estado "/>        
    </div>
    </fieldset>

    <fieldset>
        <legend>Contato </legend>
        <div class="row">
            <label>Celular: </label> <input type="number" name="Celular" id="celular" placeholder="(11) 9999 9999"/>
            <label>WhatsApp</label> 
            <input type="radio" name="opcao" id="wSim" checked />Sim
            <input type="radio" name="opcao" id="wNao" />Não
        </div>
        <div class="row">
            <label>GitHub: </label> <input type="text" name="GitHub" id="github" placeholder="https://github.com/ronaldobrunodev"/>
            <label>Linkedin</label> <input type="text" name="Linkedin" id="linkedin" placeholder="https://www.linkedin.com/in/ronaldo-bruno/"/>
        </div>
    </fieldset>

    <div class="row">
      <div class="botao">
        <button type="reset" class="limpar">
            Limpar
          </button>
          <button type="submit" class="enviar">
            Enviar 
          </button>
      </div>
    </div>
    <footer>
        <strong>Ronaldo Bruno Cardoso</strong> <br />
        <em>Projeto de HTML 5 da <strong style="color: red;">DIO</strong></em>
    </footer>   
</body>
</html>

Projeto em CSS
body{
    background-color: black;
    color: aliceblue;
    font-family:sans-serif ;
    font-size: 16px;
}
.row{
    margin: 5px;
}
label{
    width: 100px;
    text-align: right;
    display: inline-block;
    padding-right: 5px;
}

input{
    background-color: black;
    color: aqua;
    border-color: black;
}
fieldset{
    margin: 8px 35px;
    border-radius: 8px;
    border-color: lightgoldenrodyellow;
    
}
.botao{
    margin: 35px;
    text-align: center;
    font-weight: bold;
    
}
.botao .limpar{
    color: red    ;
    background-color: white;
    border-radius: 5px;
    border-color: white;
}
.botao .enviar{
    color: green;
    background-color: white;
    border-radius: 5px;
    border-color: white;
}
footer{
    text-align: center;
    padding-top: 25px;
    color: cornsilk ;
    font-weight: lighter;
}
h2{
    text-align: center;

}
