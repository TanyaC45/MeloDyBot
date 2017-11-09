# MeloDyBot
const Discord = require('MeloDy'); //เรียก MeloDyBot มาใช้
const botRem = new Discord.Client(S0eAk1qxB6qfeud6u4Q9DvAuMQ-vwCAv); //ประกาศ client ขึ้นมา
//event นี้ทำงานเมื่อ login สำเร็จ
botRem.on('ready', (S0eAk1qxB6qfeud6u4Q9DvAuMQ-vwCAv) => {
  console.log('Rem ready!');
});
/รอรับ event message เวลามีข้อความโผล่มาในแชท function นี้ก็จะทำงาน
botRem.on('message', message => { 
  if (message.content === 'จะฟังเพลง') {
    message.reply('เออๆ');
  }
});
botRem.on('message', message => { 
  if (message.content === 'จะฟังเพลง') {
    message.channel.sendMessage('เออๆ');
  }
});
botRem.login('Mzc4MTQ4NTA4MDAxMjM5MDQ5.DOXbmQ.qRUfvBNr5MLXPhf7tiNJmr0lenA');
const Discord = require('MeloDyBot');
const botRem = new Discord.Client(S0eAk1qxB6qfeud6u4Q9DvAuMQ-vwCAv);
botRem.on('ready', (S0eAk1qxB6qfeud6u4Q9DvAuMQ-vwCAv) => {
  console.log('Join!');
});
botRem.on('ready', function(S0eAk1qxB6qfeud6u4Q9DvAuMQ-vwCAv) {
  console.log('Rem ready!');
});
$ node myBot.js
