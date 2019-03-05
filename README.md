### AutoPause

AutoPause is a datapack for Minecraft 1.13+

It automatically "pauses" the game when no living players are online.

While most processes already stop when no players are nearby, some activities
continue even when there are no players connected. This means that "logging off
to eat dinner", for example, can accidentally end up skipping the night, or
"sleeping to make sure it's day when I log back on" can still surprise you with
night when you actually do come back.

This is intended for small / low-activity servers, shared by only a handful of
players, or people who almost always play as a group. There probably isn't much
point of attempting to "pause" a server where many players connect/disconnect
frequently and independently. ie: it is intended to more-closely mimic the
single-player experience when one is using a multiplayer server alone or
nearly-alone.

Pausing currently results in:

 - `/gamerule doDaylightCycle false`
 - `/gamerule doWeatherCycle false`
