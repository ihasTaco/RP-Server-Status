# RP-Discord-Server-Status
Royal Productions Server Status is an Open-Source Discord bot made in Discord.py to query Source and Minecraft game servers!

Royal Productions Server Status is a bot used and made by <a href="https://discord.gg/royal-productions-360541835371741185">Royal Productions</a>, after my favorite status bot switched teams and started charging people who have more then 5 servers (nothing against them or the fact that they are charging users, they are a great team that needs to make money!), I decided to make my own.

<a href="https://github.com/ihasTaco/RP-Discord-Server-Status#supported-games">Supported Game Servers</a><br>
<a href="https://github.com/ihasTaco/RP-Discord-Server-Status#bot-showcase">Bot Showcase</a>

# Requirements
<a href="https://www.python.org/downloads/">Python</a><br>
Tick the `Add Python to PATH` and install<br>
<a href="https://discord.com/developers/docs/intro">Discord.py</a> - pip3 install discord<br>
<a href="https://github.com/Yepoleb/python-a2s">python-a2s</a> - pip3 install python-a2s<br>
<a href="https://github.com/py-mine/mcstatus">mcstatus</a> - pip3 install mcstatus<br>
<a href="https://mariadb.com/resources/blog/how-to-connect-python-programs-to-mariadb/">mariaDB</a> - pip3 install mariadb
<a href="https://numpy.org/">numpy</a> - pip3 install numpy
<a href="https://matplotlib.org/">matplotlib</a> - pip3 install matplotlib

-- Optional -- (but still kinda required)<br>
<a href="https://www.apachefriends.org/">Xampp</a> - Used for database (Alternatively, you can also use, <a href="https://www.wampserver.com/en/">WampServer</a>, and other alternatives)<br>
<a href="https://www.heidisql.com/">HeidiSQL</a> - For accessing database, you could use phpmysql, but heidi is easier to use.<br>

# What does this bot do?
Before making this bot, I had a couple of features that I wanted to implement, before we start using it in Royal Productions.<br>
:white_check_mark: | Query all of our servers (mostly source games, but also minecraft)<br>
:white_check_mark: | Get Most (if not all) info that <a href="https://discord.gg/VQvWHQcGqY" title="Check out their discord as their bot is actually pretty good, and it has a Panel to configure servers!">Nexeum Studio's</a> bot gives access to.<br>
:white_check_mark: | Show Current Players in the server<br>
:white_check_mark: | Have a decent looking UI (Thanks Discord, for making it easy)<br>
:white_check_mark: | Be able to control the refresh rate of the servers<br>
:white_check_mark: | Easy to configure and change settings<br>
:white_check_mark: | Automatically update settings, without bot restart<br>
:white_check_mark: | Decent debug setting<br>
:white_check_mark: | Show player graph<br>

# What needs some work?
- Mostly everything is done, at this point I will be looking at other bots and trying to implement features from those bots

# Supported Games

While this *should* support all Source Games, I have tested these:
If you use this and test it on other servers, Fork this and submit a Pull Request with updated information!

AppID | Game | Works 
----- | ---- | :---: 
10 | [Counter Strike](http://store.steampowered.com/app/10/) | :white_check_mark: |
440 | [Team Fortress](http://store.steampowered.com/app/440/) | :white_check_mark: |
730 | [CS:GO](http://store.steampowered.com/app/730/) | :white_check_mark: |
107410 | [Arma 3](http://store.steampowered.com/app/107410/) | :white_check_mark: |
162107 | [DeadPoly](https://store.steampowered.com/app/1621070/) | :white_check_mark: |
304930 | [Unturned](https://store.steampowered.com/app/304930/) | :white_check_mark: |
251570 | [7 Days to Die](http://store.steampowered.com/app/251570) | :white_check_mark: |
252490 | [Rust](http://store.steampowered.com/app/252490/) | :white_check_mark: |
346110 | [Ark: Survival Evolved](http://store.steampowered.com/app/252490/) | :white_check_mark: |
~ | [Minecraft](http://www.minecraft.net/) | :white_check_mark: |


# How to use this
I am not providing hosting! So you will need to, <a href="https://discordpy.readthedocs.io/en/stable/discord.html">Set up</a> a <a href="https://discord.com/developers/applications">Bot Application on Discord</a> and make sure you have MESSAGE CONTENT INTENT enabled under bots

All the information is held in a localhost database, (like IP's, Ports, Discord Channel ID's, etc.) so make sure you change those before running the script on your public server!

All the configuration is done in the config.py! NOT THE CONFIG.INI, the config.ini is overwritten every startup but what's in the config.py file
I tried to add as much information and configuration to the config.py as possible, so if you read most of it you should be good, also you can configure pretty much everything on the bot, like to the point where it only shows the title and thats it.

# Bot Showcase
<img src="https://media.discordapp.net/attachments/917631521219813417/1048275443230457916/image.png" style="width: 250px">
<img src="https://media.discordapp.net/attachments/917631521219813417/1048275557630083242/image.png" style="width: 250px">
<img src="https://media.discordapp.net/attachments/917631521219813417/1048275684113526804/image.png" style="width: 250px">
If you use anything in my script, give me credit i guess, i don't care...
