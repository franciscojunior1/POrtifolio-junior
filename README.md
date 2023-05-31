# POrtifolio-junior 

Objetivo: Comseguir atingir a nota máxima e aprender programação no Guithub.

<h1>
  <Ul>
    <li> CSS </li>
    <li> Estrutura Basica De  Basica HTML </li>
  </Ul>
  </h1>
  
  <h2> 
  <p> Hoje na aula de programação WEb do dia 24/05/2023 o professor passou para a gente como entrar no hithub e a criar um potifólio,pois vai ser uns dos sistema avaliativo.</p>
  </h2>
Hoje no dia 26/05/2023:
Teve uma atividade bem legal, isso para testa se os alunos tinham aprendido o que tinha sido passado na ultima aula. o codigo HTML feito foi :
<!DOCTYPE html>
<html>
  <head>
    <title> programação web II </title>
    <base target="_top">
  </head>
  <body>
    
    <div>
    <label for="Nota1">nota1:</label>
    <input type="number"id="Nota1" />
    </div>

    <div>
    <label for="Peso1">Peso1:</label>
    <input type="number"id="Peso1" />
    </div>
    
    <div>
    <label for="Nota2">nota2:</label>
    <input type="number"id="Nota2" />
    </div>

    <div>
    <label for="Peso2">Peso2:</label>
    <input type="number"id="Peso2" />
    </div>

      <button onclick="somar()">somar</button>

  <script>

function somar() {
    
    var Nota1 = parseInt(document.getElementById('Nota1').value);
    var Peso1 = parseInt(document.getElementById('Peso1').value); 
    var Nota2 = parseInt(document.getElementById('Nota2').value); 
    var Peso2 = parseInt(document.getElementById('Peso2').value);

      google.script.run.somar(Nota1,Peso1,Nota2,Peso2);
}

</script>
  </body>
</html>
o codigo gs é:
function doGet() {
  return HtmlService.createHtmlOutputFromFile('index')
}
  function somar(nota1, peso1, nota2, peso2){
    var media = ((nota1 * peso1) + (nota2 * peso2)) / (peso1 + peso2);
    Logger.log('Media :'+ media)
  }
Hoje no dia 31/05/2023,fizemos mais um Codigo.
Sempre com o objetivo de aprender mais programação e ser um otimo tecnico em imformática.
