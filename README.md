# teamfight-tactics-labeled-image-dataset
A dataset of labeled images from the game Teamfight Tactics, made by Riot Games.

## Images
Images are obtained by through downloading images from the TeamfightTactics subreddit at reddit.com/r/TeamfightTactics,
and taking screenshots of videos posted there or on youtube.
If I have downloaded or screencapped an image of a game that you played and you would like me to remove it, please message me.

<br/>Images are labeled with numbers starting from 1.
<br/>There are currently 100 / 200 images labeled. 

<br/>The labels are .xml files made with @tzutalin's *labelImg* tool, which can be found here: https://github.com/tzutalin/labelImg
<br/>All labels are of in-game shots.

## Labels
Currently, I am labeling:

* The traits that each champion has, that appear on the left-hand side of the game.
* The boldened icon of the chosen trait.
* Each item that every champion holds, but not the items on the bench.
* Champions, designated as:
  * 1-star [Champion Name]
  * 2-star [Champion Name]
  * 3-star [Champion Name]
  * 1-star [Champion Name] Chosen
  * 2-star [Champion Name] Chosen
  * 3-star [Champion Name] Chosen
