# PACOTES MOVEIS
👨‍🏫ESTE APLICATIVO METEOR.JS É UMA SOLUÇÃO MULTIFUNCIONAL QUE COMBINA MAPEAMENTO DE LOCALIZAÇÃO, CAPTURA DE FOTOS E UMA EXPERIÊNCIA DE USUÁRIO ININTERRUPTA.

<img src="FOTO.jpg" align="center" width="500"> <br>

## DESCRIÇÃO:
Este aplicativo Meteor.js é uma solução multifuncional que combina mapeamento de localização, captura de fotos e uma experiência de usuário ininterrupta. Ele permite que os usuários visualizem suas coordenadas geográficas em um mapa estático, tirem fotos associadas à sua localização atual e exibam essas fotos em uma lista e em um mapa interativo. Além disso, o aplicativo utiliza técnicas para garantir que a experiência do usuário não seja interrompida por recargas durante o uso em dispositivos móveis.

Este aplicativo Meteor.js oferece três principais funcionalidades:

1. **Mapeamento de Localização:**
   - O aplicativo obtém a latitude e longitude do usuário e exibe a localização em um mapa estático, utilizando a API Geoapify.

2. **Foto com Localização:**
   - O aplicativo permite ao usuário tirar uma foto e associá-la à sua localização atual, exibindo as fotos em uma lista e em um mapa interativo.

3. **Recarregar ao Retomar:**
   - O aplicativo garante que a experiência do usuário não seja interrompida por uma recarga, adiando o envio de código ativo até que o aplicativo seja fechado e reaberto.

### CAMERA:
O pacote `./CODIGOS/simple-foto` permite tirar fotos no desktop e no celular com uma única chamada de função.

Este aplicativo de exemplo tem um botão que tira uma foto e a exibe na tela. Ele demonstra o uso do pacote Camera.

### GEOLOCATION:
O pacote `./CODIGOS/simple-map` fornece uma interface reativa à localização GPS do dispositivo.

Este aplicativo de exemplo usa a [API de mapas estáticos do Google Maps](https://developers.google.com/maps/documentation/staticmaps/) para mostrar um mapa com um marcador em sua localização atual. Ele demonstra o uso do pacote Geolocation.

### RECARREGAR AO RETOMAR:
O pacote `./CODIGOS/salomo` atrasa o envio de código ativo em dispositivos móveis até que o usuário feche e reabra o aplicativo, para que sua experiência não seja interrompida por uma recarga.

Este é o aplicativo que foi usado pela primeira vez para demonstrar a funcionalidade do Meteor Cordova no Meteor Devshop em agosto de 2014. Ele usa os pacotes Camera, Geolocation e reload-on-resume, além de pacotes locais para [Ionic Framework CSS](http://ionicframework.com/) e uma implementação simples da [API Javascript do Google Maps](https://developers.google.com/maps/documentation/javascript/).

## FUNCIONALIDADES:
### FOTO COM LOCALIZAÇÃO:
- **Tirar Foto:** Permite que o usuário tire uma foto utilizando a câmera do dispositivo.
- **Salvar Foto com Localização:** Associa a foto tirada à localização geográfica do usuário e a salva no banco de dados.
- **Exibir Fotos em Lista:** Mostra as fotos salvas em uma lista, com links para visualização no mapa.
- **Exibir Fotos no Mapa:** Mostra as fotos salvas em um mapa interativo com marcadores.

### MAPEAMENTO DE LOCALIZAÇÃO:
- **Mostrar Latitude e Longitude:** Exibe as coordenadas geográficas do usuário.
- **Mapa Estático:** Mostra a localização do usuário em um mapa estático fornecido pela API Geoapify.

### RECARREGAR AO RETOMAR
- **Experiência Ininterrupta:** Adia o envio de código ativo até que o aplicativo seja fechado e reaberto, evitando interrupções.

## COMO USAR?
1. **Instalando as Dependências:**
   - Para instalar as dependências listadas no arquivo `package.json`, você pode usar o comando `npm install` no terminal. Certifique-se de estar no diretório `CODIGOS/{E OUTRO DA SUA ESCOLHA}` e execute o seguinte comando:
   ```bash
   npm install
   ```

2. **Executando o Aplicativo:**
   - Para iniciar o aplicativo, execute o seguinte comando:
   ```bash
   meteor
   ```

   - Acesse o aplicativo no navegador visitando [http://localhost:3000/](http://localhost:3000/).

3. **Interagindo com o Aplicativo:**
   - **Mapeamento de Localização:** Acesse a página inicial do aplicativo para ver suas coordenadas e a visualização do mapa estático.
   - **Tirar Foto com Localização:** Clique no botão "Take a Photo" na página "Photo Booth" para tirar uma foto. A foto será exibida junto com sua localização em uma lista e no mapa interativo.
   - **Recarregar ao Retomar:** Use o aplicativo normalmente, sabendo que as atualizações de código não interromperão sua experiência até que o aplicativo seja fechado e reaberto.

## NÃO SABE?
- Entendemos que para manipular arquivos em `HTML`, `CSS` e outras linguagens relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE HTML E CSS](https://github.com/VILHALVA/CURSO-DE-HTML-E-CSS)
* [CURSO DE JAVASCRIPT](https://github.com/VILHALVA/CURSO-DE-JAVASCRIPT)
* [CURSO DE METEORJS](https://github.com/VILHALVA/CURSO-DE-METEORJS)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO "meteor"](https://github.com/meteor/mobile-packages)
- [PROJETO EDITADO PELO VILHALVA](https://github.com/VILHALVA)

