# Time announcer
## Format:
Web
## Description
Using a list of pre-recorded files, pronounce the time. For example, to pronounce 5:50, you would play the files ``five.mp3``, ``fif.mp3``, ``ty.mp3``.

# Spoofed JSS
Use a DNS to redirect a jamf server url to a spoofed server, to ultimately run any code needed.

## Currently working
Custom DNS server to redirect requests to local server.

## Not Currently Working
Making the local https server trusted, which means that the Jamf client won't connect (which means we can't run code).

# Update the mf timetable
Make an industrial level timetable system (Firebase maybe?)

# Minecraft Java Server - Web Manager
A web server that connects to a Minecraft Java server, allowing you to manage it.

Features:
- Has a user database with:
  - Name
  - User Avatar
  - E-mail
  - Password Hash
  - Minecraft UUID (and cached username)
  - Rank (syncs with Minecraft server)
  - 


# Make a peer-to-peer connection in JavaScript
I have no idea how this works so, definitely something to research.

# JellyCar Worlds Modifications
Take a look at some files and use a hex editor to do some cool shit. Maybe even create a custom level.

Edit saves by comparing before and after versions in a hex editor.

# Minecraft EDU server
A custom coded Minecraft EDU server that registers itself as a user, but has a custom backend. This could then also allow joining from bedrock (and potentially Java).

This could also be a plugin for pre-existing bedrock servers.

# 3D Chess, But with Minecraft mobs
3D Chess, in which instead of having chess pieces, you have a minecraft mobs which walk and jump to their places. Should probably be made *in* Minecraft.

# Jelly Physics
Using the physics of JellyCar, make a game where you can possess objects, and move them to make a road for a car to cross, 

ADD MORE DETAIL HERE

Aha Jelly SSG3

# MoldyyBot
A discord bot for MoldyyBox (hence MoldyyBot). Used for general moderation, message and action logging, automatic actions, etc.

# Train system GUI
An app that allows you to control LEGO trains and track switches, ensuring that no two trains ever collide, nor do any trains fall off the end of a track. This should have an editor which saves the track layout, the train layout, position, and bluetooth id, and the switch ids to a file. This should then also use a map view to show where trains are and which switches are toggled, and a panel to control train speed, colour, and other features accessible from their control block (eg. lights).

# Circuitry in game
A realistic 3D (possibly VR) game, that includes the ability to make life like circuits, giving the player a shop that sells breadboards, motherboards, components, motors, lights, wires, etc...

# A Nintendo Joy-Con hub
This allows you to slot the Joy-Cons into the hub like the official grip, but it gets the inputs as if the Joy-Cons were attached to the Nintendo Switch.

This could allow for USB-C connections from the Joy-Cons, a screen in the hub, battery indicators and macros.

# Parkour Checkpoints Plugin
A server plugin to keep track of checkpoints in a parkour map, and if a player has gone too far away from the parkour (probably cause they fell L), teleport them back to their last checkpoint.

# Decky Core
Minecraft Java core plugin.

## Minecraft <--> Discord <--> Web
Allow the chat and moderation system to be used throughout all three platforms. In this case, the web server would be the main and the Minecraft Server would use a websocket to send and receive data from the web server. A discord bot would be used to integrate Discord to the Web Server, which would in turn connect to the Minecraft Server.

# MOLDYYBOX ENHANCEMENTS
## Add dropping/trading
This would obviously need a whitelist of items, which can be traded from and to a person. This would help prevent server griefing.

Eg. A God player would be able to give someone Cloud, but an angel player would not be able to recieve it.

## Commands
### /quicktrash
This essentially trashes all non-valuable items.

Per-player customisable.

### /trashistory
Get a history of the past ~100 items put in the trash. This would allow the player to take the item back.

This would be in a chest window.

### /pvptoggle
If we can find a proper way to have this used, in which it will not kill the server, we can use this.

## A web GUI for AquaCore
This would be a website, accessible by getting a code from in-game as a staff member. This would then allow you to customise permissions and ranks (and other assorted things) without using commands for them.

This could then also show the location of players on a bird's eye view, allowing you to select a player and then manage and see info about them (messages, location, name, UUID, recently run commands, how long their current session is).

This could then also allow staff to talk in chat without being in the game.

## A scoreboard GUI
This can show playtime, Rank, level, kdr, blocks mined (or some cool statistic) and some tips on what you should be doing.

## Crates
Daily/weekly and ranked crates. This would have a crate that you get for reaching a rank, and paid ranks would also get a daily/weekly crate.

## Paid ranks/donations???
Not sure about this one, but we do need a source of income for our servers.

## Keeping players in-bounds.
Space out areas so that no two are ever within the same render distance (capped by server), and ensure that anybody out of bounds is teleported back in.

## Better trading system
Use a chest window to display the trades, which would allow the player to select a pickaxe, which upon 

## Bug report tokens
A reward for reporting bugs

## Rage Notifs
Make Rage notifications show up in the bottom bar rather than chat.

## Leaderboards
For playtime, blocks mined, coins and completion %.

## PARKOUR!!!
Add some parkour about the place. Disable fly mode in these areas.