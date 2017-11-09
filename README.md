# MeloDyBot
const Discord = require('discord.js'); //เรียก MeloDyBot มาใช้
const botRem = new Discord.Client(); //ประกาศ client ขึ้นมา
//event นี้ทำงานเมื่อ login สำเร็จ
botRem.on('ready', () => {
  console.log('Rem ready!');
});
/รอรับ event message เวลามีข้อความโผล่มาในแชท function นี้ก็จะทำงาน
botRem.on('message', message => { 
  if (message.content === 'จะฟังเพลง') {
    message.reply('เออๆ');
  }
});
botRem.login('เอา token มาใส่ตรงนี้');
const Discord = require('MeloDyBot');
const botRem = new Discord.Client();
botRem.on('ready', () => {
  console.log('Join!');
});
botRem.on('ready', function() {
  console.log('Rem ready!');
});
$ node myBot.js
