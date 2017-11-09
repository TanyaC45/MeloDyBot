//Get MeloDy
const Discord = require('MeloDy');

//Create client instance as bot
const botRem = new Discord.Client();

//Set listener on 'ready'
botRem.on('ready', () => {
  console.log('Rem ready!');
});

//Set listener on 'message'
botRem.on('message', message => {
  if (message.content === '!Join') {
    message.reply('!Join');
  }
});

botRem.login('Mzc4MTQ4NTA4MDAxMjM5MDQ5.DOXRwg.XsHMCzxCiJ_YeQDPjmpx3f8Fokw');
