## RepuZM
* RepuZM é um aplicativo móvel para anúncio de vagas de república.
* Desenvolvido em React Native / Expo.
### Projeto de Desenvolvimento do aplicativo:

### Apresentação de "Hello World" em React Native.
Eu instalei para o desenvolvimento do projeto tanto o React Native como seu framework [`Expo`](https://expo.dev/). A instação do React Native foi via [`Chocolatey`](https://en.wikipedia.org/wiki/Chocolatey) usando um tutorial do curso da Udemy do [Matheus Fraga](https://sujeitoprogramador.com/ambiente-windows/) para Windows. Essa instalação é mais pesada que a do Expo mas me permite usar o Emulador do Android se eu não quiser usar o celular (físico). Uma rápida olhada no tutorial que cito mostra que instalei 04 programas:
* Node.js.
* Python 2.
* Openjdk11.
* Android Studio.

Depois disso parti para a instalação do Expo (veja no google a infinidade de posts dicustindo quando usar React Native versus Expo). O Expo é um programa indicado para desenvolvedores poucos experientes em mobile (meu caso em 2022) e os passos que utilizei na instalação foram:

[01]. Via CMD (como administrador) digito o comando (instalação global na máquina): `npm install -g expo-cli`

[02]. Defino uma pasta para criar o meu novo projeto (RepuZM) com Expo: `expo init RepuZM`

[03]. Escolho um template (ou pode usar o defusr: Blank dando  `Enter`) e coloco o nome do meu projeto (via teclado embora nem apareça direito). 

[04]. Concluída essa instalação entro na pasta do projeto e vou para a IDE em uso (no meu caso o Visual Code via: `code .` ou abrindo a pasta no seu programa de uso).

[05]. Como crei o projeto com `npm` para rodar o projeto no seu diretório uso: `npm start`. Uma tela no navegador é aberta com um QRcode. Para usar algum celular físico com Android para desenvolvimento basta conectar o celular na mesma rede em uso pelo computador e instalar o [Expo](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR&gl=US). Instalado o aplicativo basta ler o QRcode e a IDE (em uso) e o celular estarão conectados.

[06]. Como meu projeto já foi criado basta ir na IDE em uso (no meu caso o Visual Code), na pasta `App.js` e escrever o nosso "Hello World" em React Native (via Expo).










