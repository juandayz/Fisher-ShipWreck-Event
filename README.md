# Fisher-ShipWreck-Event

PLEASE DONATE: https://github.com/juandayz/Fisher-ShipWreck-Event/blob/master/DONATION.md


Spawn a fishing boat wreack in the ocean with some customizable loot inside.

You need change the main coord in this line by your own. 

```ruby
_position = [6821.376, 8596.1465, -1.5752504];
```
And check the loot items. Thers a few for overpoch.

INSTALL:

Open your init.sqf and call the event from:

```ruby
EpochUseEvents = true; //Enable event scheduler. Define custom scripts in dayz_server\modules to run on a schedule.
EpochEvents = [["any","any","any","any",45,"server_BoatWreck"]];


Now Drop server_BoatWreck.sqf into dayz_server.pbo\modules\
