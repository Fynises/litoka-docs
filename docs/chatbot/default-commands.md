---
sidebar_position: 2
---

# Default Commands

### Toggle

Each command has a toggle switch to enable/disable a command entirely.  
pressing the toggle switch will automatically update your configuration.  

### Permissions

Each command gives you further ability to configure by pressing the cogwheel to the right of the toggle switch.  

The permissions represent which user groups are allowed to execute the command and the cooldown for that user group.  
Current minimum cooldown is set to 5 seconds. (the broadcaster is not subject to cooldowns)
  
If a user belongs to multiple groups, the cooldown is selected in this order: 
1. Moderator
2. VIP
3. Subscriber
4. Everyone

### Cooldown

The cooldown is applied to the whole channel, and not on a per-command basis.
  
The exception to cooldown is the [shoutout command](../shoutout-player/introduction.md)
where the cooldown only applies to the chatbot response, not the execution of the shoutout to the stream.
