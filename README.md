let Discord = require("discord.js");
let client = new Discord.Client();



Client.on("message", message => {
  
  if (message.content === "Hello") {
    
  message.channel.send("Hello Do you want to teach some technique")
    
  }
  
}}
          
          
          
  Client.login("")
