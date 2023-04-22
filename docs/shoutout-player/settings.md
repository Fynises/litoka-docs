---
sidebar_position: 2
---

# Settings

The following settings are available  
  
Overrides will be mentioned here, to get an understanding of overrides and its settings see [here](./overrides.md)

### Enable automatic shoutout on channel raid
Note: Not implemented yet  
When enabled, if another user raids you, Litoka will automatically shoutout the raiding user using the settings

### Enable chat resoponse
When enabled, Litoka will respond in chat the user being shouted-out.  
Other chatbots may have a feature for this already, but if the shoutout command is used with an override, then other chatbots might not function correctly. 

### Default clip muted
Runs clip shoutouts in a muted mode.  
can be overriden with `-cu`

### Mode
- Clip: Plays a random clip
- Name Only: Displays the Name and profile picture of the user being shouted out without a clip 
- Message Only: Disables output, this is intended to allow shoutouts by chatbot response only, while allowing overrides to still be used

### Use max clip duration
When enabled, will place a cap on how long a clip can be played for

### Duration settings
#### Max clip duration
Sets the maximum clip length if 'Use max clip duration' is enabled
#### Clip end delay
[Why this is needed.](./advanced-info.md)  
The approximate time required for a clip to load, adjust to your needs.
Increase if you think clips are ending too early.
Decrease if you are regularly seeing the clip end menu.
#### Name only duration
Determines how long a name only shoutout will stay on the screen

### Filter Settings
This setting determines the algorithm for randomly picking clips.  
Due to Twitch API limitations, there is only one algorithm
#### Top Viewed
Picks randomly from the user's top viewed clips within a specified range. (Maximum: 300)