# ClipShout
Twitch bot with clip playing capabilities
[![image](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://www.twitch.tv/arkkis) 
[Support developer](https://subs.twitch.tv/arkkis)  

## How to Setup
- Add Browser as a source to your streaming software
- Fill `https://arkkis.com/clipshout/?channel=YOURTWITCHCHANNEL` in URL field
  - Remember to replace YOURTWITCHCHANNEL with your own channelname ;)
- Set Width and Height to (for proper aspect ratio)
  - 1920 and 1080
  - 1280 and 720
- Press OK and you are done

## How to Use
Use command `!so CHANNELNAME` in your Twitch chat to play shoutout clip.

## How to allow bot messaging to your chat (optional)
- Right click your browser source in your streaming software
- Click `Interact`
- Move your mouse to middle of the window and click `Connect with Twitch`
- Login to your Twitch account
- Done!

## How to disconnect bot from Twitch account (optional if you have connected bot to Twitch)
- Right click your browser source in your streaming software
- Click `Interact`
- Move your mouse to middle of the window and click `Reset`
- Done!

## Options
#### Options are added to your browser sources URL field with separating character `&`
- channel=twitchchannel **(Required)**
  - Sets your Twitch channel with bot
- quality=high
  - Values: high | medium | low
- chatshout=false
  - Shoutout with link to chat, requires "Connect to Twitch"
- durationlimit=60
  - Does not play xx seconds longer clips
- cliproll=true
  - Starts looping your clips infinitely
  - This disables all other functions
- random=false
  - If cliproll is true, plays clips from most viewed to least viewed
- shoutOnRaid=true
  - Plays clip automatically after 10 seconds you are raided
- alwaysTopClip=true
  - Always plays the most viewed clip

#### Examples
```https://arkkis.com/clipshout/?channel=arkkis&quality=low&durationlimit=30```  
```https://arkkis.com/clipshout/?channel=tiitirun&quality=high&chatshout=true```  
```https://arkkis.com/clipshout/?channel=slipoverih&shoutOnRaid=true&alwaysTopClip=true```  
```https://arkkis.com/clipshout/?channel=bamxtreme&cliproll=true```  

## Frequently asked questions
- Clips are lagging or buffering?
  - Set quality to lower (see [Options](#options))
