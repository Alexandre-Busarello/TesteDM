Esta aplicação foi escrita utilizando angularJS, less e grunt para minificação e junção dos arquivos .js e .css.
Para rodar esta aplicação basta executar o npm install no diretório raiz, e iniciar o servidor web utilizando o comando "http-server" no cmd na raiz do projeto. Com isso um servidor http simples ira iniciar a aplicação.

Após isso a aplicação podera ser acessada em: localhost:8080.
* Por se tratar de um servidos HTTP simples, somente é possível acessar a aplicação através da raiz http://localhost:8080. 
* O roteamento na angular é feito no angular, conforme pode ser observado ao navegar na aplicação.

Caso não se deseje rodar a aplicação utilizando um servidor, pode-se utilizar o seguinte projeto:
https://github.com/Alexandre-Busarello/TesteDM-local---firefox-only-

Com esse projeto é possível rodar a aplicação sem um servidor web por trás, porem apenas no firefox. O chrome e os outros browsers bloqueiam o roteamento do angular se não existir um servidor web por trás.

PS: A pasta dist é a versão com os arquivos .js e .css minificados e unificados.
