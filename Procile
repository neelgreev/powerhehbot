worker: python powerhehbot.py

import discord
from discord.ext import commands
import asyncio
 
bot=commands.Bot(command_prefix='heh!')
 
@bot.event
async def on_ready():
    print('Logged in as:')
    print(bot.user.name)
    print(bot.user.id)
    print('--------------------')
   
@bot.command(pass_context=True)
async def ping():
    await bot.say('PingPong')
    await bot.say('Dont Ping me you idiot :P')
@bot.command()
async def hi():
	
	await bot.say('hi there')
@bot.command()
async def whatsup():
	await bot.say('Nothing Just Keeping Myself on until somebody turns me off')
@bot.command()
async def who_are_you():
	await bot.say('I am Power Gamers HEH bot')
@bot.command()
async def prefix():
	await bot.say('My Prefix is heh!')
	await bot.say('For example:- heh!yourcommand')
@bot.command()
async def countnumbers():
		await bot.say('1,2,3,4,5,6,7,8,9,10')
		await bot.say('11,12,13,14,15,16,17,18,19,20')
@bot.command()
async def tableflip():
	await bot.say('(╯°□°）╯︵ ┻━┻')
@bot.command()
async def unfliptable():
	await bot.say(' ┬─┬ ノ( ゜-゜ノ)')
   
@bot.command(pass_context=True)
async def mute(ctx,target:discord.Member):
    role=discord.utils.get(ctx.message.server.roles,name='Muted')
   
    await bot.add_roles(target,role)
   
@bot.command(pass_context=True)
async def warn(ctx,target:discord.Member):
    await bot.send_message(target,'Warning!!')
   
@bot.command(pass_context=True)
async def kick(ctx,target:discord.Member):
    await bot.kick(target)
   
@bot.command(pass_context=True)
async def ban(ctx,target:discord.Member):
    await bot.ban(target)
   

client.run(os.getenv('Token'))

