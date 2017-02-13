# sigton-bot
This is the discord bot for managing orders and chat moderation
if (command === "foo") {
    let modRole = message.guild.roles.find("name", "Mods");
    if(message.member.roles.has(modRole.id)) {
      message.channel.sendMessage("bar!").catch(console.error);
    } else {
      message.reply("You pleb, you don't have the permission to use this command.").catch(console.error);
    }
