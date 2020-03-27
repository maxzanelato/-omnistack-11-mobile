# omnistack-11-mobile

Tecnologias utilizadas:
* React Native;
* Expo para Windows;
* Node e NPM;
* Expo para IOS (Servirá para ver o live loading da aplicação).

Requisitos:
* Ter o expo instalado no Windows;
* Ter o expo instalado no iPhone;
* Ter NodeJS, NPM e yarn;
* Ter o back-end rodando.

O teste foi feito com dispositivo IOS, logo, para sua execução foram necessário os seguintes passos:
1. Executar o back-end;
2. Executar "yarn start" para que o expo possa ser inicializado e abra uma porta de conexão com o dispositivo mobile;
3. Ler o QRCode através da câmera na página que irá abrir;
4. O celular abrirá o expo e deverá selecionar a aplicação.

OBS.: No arquivo "api.js", a "baseUrl" que é passada para o axios deverá ser o IP da máquina. Nesse caso, no Windows, como não há como colocar localhost, foi acessado o comando no terminado "ipconfig", selecionado o IP e adicionado na "baseUrl".
