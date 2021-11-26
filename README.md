- 👋 Hi, I’m @KitsuneFire1031 , I need help with a line of code for a Discord bot! please help me (preferably a French one because I am French)



import discord
from discord.ext import commands

bot = commands.bot{command_prefix = "^", description = "BOT les Infecté(e)s des Volcans"}

@bot.event 
async def on_ready ():
    print("le bot est prêt !")
    await
bot.change_presences(status=discord.Status.onligne,activity=discord.Game("Se faire coder par KSFR") )

jeton = (ton jeton (token))

bot.run(jeton)

    @bot.commande()
    async def apo(ctx):
        await ctx.send("calypse!")

        bot.run("[token of my bot]")

default_intents = discord.Intents.default()

default_intents.members = True

client = discord.Client(intents=default_intents)

@client.event
async def on_member_join(member):
    print(f"L'utilisateur {member.display_name} a rejoint le serveur ! Nouv avons un nouveau/velle infectée !")
