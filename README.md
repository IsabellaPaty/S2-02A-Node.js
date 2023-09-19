# S2-02A-Node.js

Passo a passo  

1) entrar na pasta onde o node-env esta localizado (o meu esta dentro da raiz)
   ex: cd nodejs-env/

2) Ativar o node-env seguindo os seguintes comandos(dentro da pasta onde o node nodejs-env está)
   source bin/activate

3) abrir o nano do arquivo "index.js" (colocar sudo na frente caso o arquivo não pertença a você)
   ex: nano index.js
   
4) dentro do nano colocar o código js da sua preferência e salvar (colocando a porta da sua preferência)

   ex:
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(8010);

5) para testar o arquivo digite:
   node "nome do arquivo"
   
6) Para testar o funcionamento do código entre no seu navegador e digite:
   localhost:'numero da porta escolhida'
   
