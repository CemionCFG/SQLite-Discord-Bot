# Discord Database Bot



Discord Database Bot is a discord bot, able to connect and manage any SQLite Database.
  - No Premium
  - Access to SQLite .db file
  - Full SQLite shell access

![](https://discordpy.readthedocs.io/en/latest/_images/snake.png)

## About
Discord Database Bot is a lightweight python based bot that's built by [Yon Liud](https://github.com/YonLiud) for easier access to SQLite Shell, without the hassle of remote accessing.
A simple setup is required for running the bot,

# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Setup
Discord Database Bot uses a small number of python modules to work properly:

* [Valid Token](https://discordpy.readthedocs.io/en/latest/discord.html) - A Valid discord bot
* [Python](https://www.python.org/) - Python, duh
* [Discord.py](https://pypi.org/project/discord.py/) - Discord Module
* [SQLite3](https://www.sqlite.org/index.html) - The Database Library

And of course Discord Database Bot itself is open source with a [public repository](https://github.com/YonLiud/Discord-Database-Bot/) 
on GitHub.

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Installation

Discord Database Bot requires [Python3](https://www.python.org/) & [Discord.py](https://pypi.org/project/discord.py/) to run.

#### Install the modules.

```sh
$ cd Discord-Database-Bot
$ pip install discord.py
```
#### Insert bot's token
How to get a token: https://discordpy.readthedocs.io/en/latest/discord.html
```sh
$ cd Discord-Database-Bot
$ echo "[TOKEN HERE]" > token.txt
```
#Example of token command:
```cmd
echo "NzU0NjIzNTQzNTI2MDMxNDgy.X13b8Q.e0V0cwwmc_BYeMHwvJovFQhLBfk" > token.txt
```
(the token is no longer valid, **DO NOT ATTEMPT TO INSERT TOKEN TO PROJECT**)
#### ![#c5f015](https://via.placeholder.com/15/FFFF00/000000?text=+) Running Bot

```sh
$ python3 app.py
```
The bot will create a role called 'dmb'
#### ![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+) In Server Use

> For being able to execute any command by Discord Database Bot, you must assign users with the created 'dmb' role,

for help:
```sql
sql>help
```

#### ![#9400D3](https://via.placeholder.com/15/9400D3/000000?text=+) Basic Commands
| Plugin | README |
| ------ | ------ |
| Create Table | CREATE TABLE IF NOT EXISTS name (parameters)|
| Select a Value from Table | SELECT column-name FROM table-name WHERE type='identifier' |
| Insert a Value to row | INSERT INTO table-name (parameters) VALUES (values of parameters)  |

#### ![#FF69B4](https://via.placeholder.com/15/FF69B4/000000?text=+) Help

for help, run the command ``sql>help``,
for support, please visit [alTab Developments Website](https://altab.dev/), all of the needed information is there

License
----

MIT


**Free Software, Hell Yeah!**
