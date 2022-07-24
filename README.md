# GDDB
GDDB (Geometry dash Database), is a collection of featured levels but rated with better standards that focuses on balancing the gameplay and the look of the level.
I feel that the current rating system in geometry dash is not focused enough on how fun playing the level is, in so many levels I spend more time trying to process whats a decoration and whats not, more time trying to see where I am than trying to actually play.

## So whats GDDB going to do
GDDB won't magicly make the rating system better for creators but as a player if you want to play levels that are both fun to play and aren't an eyesore, you can see look at the [Github page of this repo](https://Dev7z.github.io/gddb/).


### How will the levels be rated in the GDDB system
Each level will be in a json file named after their ID, for example the level "ReTraY" will be "6508283.json"
The file will look like this

```json
{
    "name": "ReTray",
    "visibility": "10",
    "no-repetitive-or-afk-or-annoying-parts": "5",
    "gameplay-overall": "6",
    "music-sync": "7",
    "polish": "7",
    "useless-or-annoying-triggers-or-decorations": "10",
    "score": "75",
    "difficulty": "1"
}
```

It contains (in order):
    The name of the level
    How visible the level is (0-10)
        In terms of how visible the player is and how visible the upcoming obstacles are
        A score of 0 means that almost nothing is visible in the level and playing the it's layout significantly reduces it's difficuly
        A score of 10 means that everything from the player to all the upcoming obstacles are visible
        Most levels in this DB should have a relatively high score since I prefer to rate the good levels
    Whether a level is fun to play or not (keeping the difficulty of the level in mind)
        Even though some levels are technically not repetitive
    
