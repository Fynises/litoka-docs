---
sidebar_position: 3
---

# Overrides

Overrides provide the ability for the shoutout to be modified without needing a settings change by the broadcaster.  
  
Overrides need to be enabled by the broadcaster in order to be used

```
-c # use clip

-cm # use clip (force muted)

-cu # use clip (force unmuted)
```
Forces the shoutout to be a clip, useful if the default mode is set to 'Name Only' or 'Message Only'  
Note: these will not override max clip duration, a feature for this is planned.

```
-n # use name only
```
Forces the shoutout to the 'Name Only' mode

```
-m # use message only
```
Forces the shoutout to the 'Message Only' mode.  

```
-d # direct clip shoutout
```
Runs a direct clip shoutout.  
'direct' meaning that the identifier is a clip ID or URL instead of a user.  
Examples of valid commands
```
!so -d https://clips.twitch.tv/AwkwardHelplessSalamanderSwiftRage

!so -d https://twitch.tv/litokabot/clip/AwkwardHelplessSalamanderSwiftRage

!so -d AwkwardHelplessSalamanderSwiftRage
```
Note that a username is not required if running in direct mode
