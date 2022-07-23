# Discord-Voice-bot
const { Client } = require("discord.js") const client1 = new Client() client1.login("Bot Token")  client1.on("ready", async () => {       client1.channels.cache.get("Ur voice id").join()       console.log(`${client1.user.username}`)
