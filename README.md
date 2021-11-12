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

<li>npm install electron-packager --save-dev</li>
<br>

<li>npm install electron-packager -g</li>
<br>
E empacote ou implemente usando:
<br>
<li>electron-packager DIRETORIO NOMEDOAPP --platform=win32 --Arch=x86_64</li>
<br>
O comando acima pode gerar um erro

Arco não suportado = x86_64 (string); deve ser uma sequência correspondente: ia32, x64, armv7l, arm64, mips64el

Sugerido o uso de uma das opções de ia32, x64, armv7l, arm64, mips64el

<li>electron-packager <sourcedir> <appname> --platform=win32 --Arch=x64</li>
