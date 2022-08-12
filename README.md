# ClipShout
Twitch bot with clip playing capabilities

## How to Setup
- Add Browser as a source to your streaming software
- Fill `https://arkkis.com/clipshout/?channel=YOURTWITCHCHANNEL` in URL field
- Press OK and you are done

## How to Use
Use command `!so CHANNELNAME` in your Twitch chat to play shoutout clip.

## How to allow bot messaging to your chat (optional)
- Right click your browser source in your streaming software
- Click `Interact`
- Move your mouse to middle of the window and click `Connect with Twitch`
- Login to your Twitch account
- Done!

## Options
### Options are added to your browser sources URL field with separating character `&`
- (Required) channel=twitchchannel
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

#### Example
```https://arkkis.com/clipshout/?channel=arkkis&quality=low&chatshout=true&durationlimit=30```
