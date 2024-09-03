# drcwhitebordersRLT
DRC White Borders RLT theme created by Splatbeef

To contact me about the theme, please join the RLT Discord server and go to the relevant forum post in themes-discussion. https://discord.gg/XXjCetGJ8F

## 1. Championship Type

The theme changes background depending on your chosen championship type.
Currently available:
- Generic
- F1 2024
- F1 2023
- Super Formula
- ACC GT3

The "Generic" championship uses generic backgrounds and your database logo.

Suggestions are welcome! Please post these in the forum post for the theme in the RLT Discord server

## 2. Adding custom league logos

By default, the theme uses the logo of the championship (eg. the F1 logo). If you want to use a custom logo for your league, put a logo titled leaguelogo.png in images/league_logos/{championship}.
To add logos or sponsors to the white border, please make a copy of border_blank.png and border_blank2.png in images/bg. Add your logos to these images and save them as border.png and border2.png respectively. Then add them to their championship folder in images/bg.
Finally, enable the "add sponsors/league logos" option in the theme settings.

## 3. Adding custom teams and logos

On the database tab, create a team and set the name and UniqueId. Example: Name: "Andretti Global", UniqueId: "andretti.global.2024".
To add a logo for your new team, add a png image with the UniqueId as name to the images/logotypes/teams folder. Example: "andretti.global.2024.png". The logo shows up after restarting your RLT application.

## 4. Track maps

If you are using a track that is not in the base app, and you want to use the "Event Information" render, please follow these steps:
1. Check in images/logotypes/circuits whether I have already put that track in. If it is in there, create the track in RLT with the UniqueId given by the image name
2. If it was not in there, either send me a message with a request (if you are not in a hurry), or add the map yourself (and name the image after the track UniqueId). The maps in the theme are all taken from wikipedia.

## 5. Using reserves as solo drivers

By enabling this option, several changes will be made to pretend like reserves are actually full-time drivers without a team. This will change the reserves render, and will enable driver logos.
These driver logos will come in the place where the team logo normally is. To add driver logos, create the logo as a png file. Name it after the driver name, and put it in images/driver_logos/{championship}
