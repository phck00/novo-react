# novo-react
function obterMensagem() {
  return "Olá! Esta é a mensagem retornada pela função.";
}

export default obterMensagem;

import obterMensagem from './src/mensagem.js';

console.log(obterMensagem()); // Isso imprimirá "Olá! Esta é a mensagem retornada pela função."
