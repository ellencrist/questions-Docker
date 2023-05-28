# questions-Docker


<h1>Exercícios 1</h1>

  <div>
   Qual o comportamento esperado quando persistimos dados com Docker volume e o container para de rodar?
   <p>R: Os arquivos permanecem na pasta source.</p>
  </div>
  <br>
 
  <div>
    A instrução WORKDIR no Dockerfile faz o quê?
    <p>R: Acessarmos um diretório/pasta dentro do container.</p>
  </div>
  
  <br>
  <div>
    Para que serve a instrução RUN no Dockerfile?
    <p>R: Para executar instruções durante o processo de build/construção.</p>
  </div>
    
   <br>
    <div>
      Garantir segurança é importante. Qual comando do Docker verifica nossas imagens, fazendo uma checagem de componentes?
      <p>R: docker scan.</p>
    </div>
    <br>
   <div>
      São ferramentas para uso de containers:
     <p> R: Cri-o e Docker.</p>
   </div>
   
   <h2>Exercícios 2</h2>
     <div>
     Iremos utilizar containers em hosts distribuídos. Qual dos drivers deveria ser utilizado para que os containers se comuniquem de forma efetiva?
      <p>R:Overlay.</p>
    </div>
    <br>
   
   <div>
     Ao segregarmos containers conseguimos ter uma série de benefícios, quais se aplicam?
    <p>R: Maior flexibilidade e facilidade em dar manutenção, pois temos contextos menores e melhor configurados</p>  
</div>
   
   <div>
     Sobre docker-compose é incorreto afirmar que:
     <p>R: Não permite o uso de volumes no Docker </p>    
  </div>

<br>
    <div>
       O comando docker-compose rm -rf faz com que?
     <p>R: Os containers serão removidos do sistema. </p>    
</div>
<br>
  <div>
    O Docker não deve ser utilizado para?
    <p>R: Sistemas aglutinados e com poucos recursos, já que a energia para o desacoplamento seria grande (Ex: um ERP). </p>
  </div>
