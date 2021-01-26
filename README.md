const Discord = require('discord.js'); 

const client = new Discord.Client();


client.once('ready' , () => {
    console.log('soup is online');
});

client.on('message', message => {
    if (message.content == 'soup') {
        message.reply(`hai`);
    }
});

client.on('message', message => {
    if (message.content == 'tpn no esta chido') {
        message.reply(`omg claro que no esta bien chido`);
    }
});

client.on('message', message => {
    if (message.content == 'eyesoup') {
        message.reply(message.reply(`\`\`\`
        __   __  __     __    ____    ___   __  __  _____   
        /'__`\/\ \/\ \  /'__`\ /',__\  / __`\/\ \/\ \/\ '__`\ 
       /\  __/\ \ \_\ \/\  __//\__, `\/\ \L\ \ \ \_\ \ \ \L\ \
       \ \____\\/`____ \ \____\/\____/\ \____/\ \____/\ \ ,__/
        \/____/ `/___/> \/____/\/___/  \/___/  \/___/  \ \ \/ 
                   /\___/                               \ \_\ 
                   \/__/                                 \/_/ 
      \`\`\``))
    }
})

