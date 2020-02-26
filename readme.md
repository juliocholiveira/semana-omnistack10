### PREPARANDO O AMBIENTE 

# Instalar o HomeBrew
https://brew.sh/

# Instalação do NodeJS 12.14.1 LTS
brew install node@12

# Instalação do Yarn
https://yarnpkg.com

brew install yarn --ignore-dependencies ou brew upgrade yarn

### PREPARANDO AS FERRAMENTAS DE DEV

# Instalar o VSCode
# Instalar a extenção Dacula Official
# Instalar a extenção Material Icon Theme
# Instalar os snipets da RocketSeat
# Link para vídeo de configuração de vscode https://www.youtube.com/watch?v=c7P03kkrEG8
# Habilitar "Install Code Command in Path" com Shift+Command+P

# No chrome, instalar a extensão JSON Viewer
# No chrome, instalar a extenção React Developer Tools
# Baixar e instalar o https://insomnia.rest/

# Baixar e instalar o MongoDB Compass Community https://www.mongodb.com/download-center/compass

### CRIANDO O PROJETO BACKEND

# Criar pasta com o nome SemanaOmniStack10
# Criar subpasta Backend
# Dentro da pasta Backend criar projeto com yarn
yarn init -y

# Instalar o Express
yarn add express

# Instalar o NodeMon (biblioteca que atualiza o servidor automaticamente depois de alguma alteração)
yarn add nodemon -D

#   Para executar o index com o NodeMon
    yarn nodemon index.js

#   ou adicione este script no package.json
    "scripts": {
        "dev": "nodemon index.js"
    }

#   execute o comando
    yarn dev    

# Instalar o MongoDB (Não-relacional)
https://www.mongodb.com/cloud/atlas

# Instalar o Mongose
yarn add mongoose

# Instalar Axios
yarn add axios

# Instalar o cors
yarn add cors

# Instalar o Socket.io
yarn add socket.io

### CRIANDO O PROJETO WEB

#   Criar o projeto com yarn
yarn create react-app web

# Instalar Axios
yarn add axios 


### CRIANDO O PROJETO WEB

# Instalar o Expo (https://docs.expo.io/versions/latest/)
yarn global add expo-cli

# Adicional o Yarn Global ao PATH (https://classic.yarnpkg.com/en/docs/cli/global/)
export PATH="$(yarn global bin):$PATH"

# Instalar o React-Navigation (https://reactnavigation.org/docs/en/getting-started.html#installation)
yarn add @react-navigation/native

expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

yarn add @react-navigation/stack

# Instalar o MapView do Expo (https://docs.expo.io/versions/v36.0.0/sdk/map-view/)
expo install react-native-maps

# Instalar o Expo Location
expo install expo-location

# Instalar o Expo WebView
expo install react-native-webview

# Instalar o Axios
yarn add axios

# Instalar o Socket.io-client
yarn add socket.io-client

TODO: SUBMETER CÓDIGO PARA O GITHUB
TODO: SUBMETER APP PARA HEROKU
TODO: VER QUAL SERVER É BOM PARA HOSPEDAR PÁGINAS REACT (GITHUB PAGES)
TODO: SUBMETER PARA LOJAS
TODO: ESTUDAR O OTA (OVER THE AIR UPDATE)
TODO: MOVER INPUT DE ACORDO COM A EXIBIÇÃO DO TECLADO (FALTA 8 MIN DO VIDEO)
TODO: BOTÃO PARA CENTRALIZAR
TODO: UTILIZAR ARQUIVOS .ENV PARA CONFIGURAR A URL DA APLICAÇÃO MOBILE