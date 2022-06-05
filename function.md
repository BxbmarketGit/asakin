# MAKE BY BXBMARKET

[![N|Solid](https://bxbmarket.com/wp-content/uploads/2022/01/LOGO-300x111.png)]()

# List Function
* [getBot](#getbot)
* [getBots](#getbots)
* [sendPacket](#sendpacket)
* [getInventory](#getinventory)
* [getObject](#getobject)
* [getObjects](#getobjects)
* [getPlayers]()
* 

## getBot

```
getBot() // local bot
getBot("targetbotname") // targetbot
getBot().name // bot name
getBot().world // currentWorld of bot
getBot().status // status of bot
getBot().x // pos x of bot
getBot().y // pos y of bot
```

Example :
```lua
say(getBot().name)
say(getBot().world)
say(getBot("NameBot").world
```


## getBots

```lua
getBots()
bot.name // bot name
bot.world // currentWorld of bot
bot.status // status of bot
bot.x // pos x of bot
bot.y // pos y of bot
``

