# Instalando o Electron

### Clone this repository
git clone https://github.com/electron/electron-quick-start
### Go into the repository
cd electron-quick-start
### Install dependencies
npm install
### Run the app
npm start

# Compilar um aplicativo Electron 

Você precisa usar Electron Packager .

Instale usando:

# for use in npm scripts
npm install electron-packager --save-dev

# for use from cli
npm install electron-packager -g

E empacote ou implemente usando:

electron-packager DIRETORIO NOMEDOAPP --platform=win32 --Arch=x86_64

O comando acima pode gerar um erro

Arco não suportado = x86_64 (string); deve ser uma sequência correspondente: ia32, x64, armv7l, arm64, mips64el

Sugerido o uso de uma das opções de ia32, x64, armv7l, arm64, mips64el

electron-packager <sourcedir> <appname> --platform=win32 --Arch=x64
