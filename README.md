# GDDB
GDDB (Geometry dash Database), is a collection of featured levels but rated with better standards that focuses on balancing the gameplay and the look of the level.
I feel that the current rating system in geometry dash is not focused enough on how fun playing the level is, in so many levels I spend more time trying to process whats a decoration and whats not, more time trying to see where I am than trying to actually play.

## So whats GDDB going to do
GDDB won't magicly make the rating system better for creators but as a player if you want to play levels that are both fun to play and aren't an eyesore, you can see look at the [Github page of this repo](https://Dev7z.github.io/gddb/).
In the future I'm planning on integrating this to the game itself for windows and possibly for jailbroken ios devices.


# How will the levels be rated in the GDDB system
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

\n
This is the rubrik for creators and users that want to commit levels:

    The name of the level
    
    How visible the level is (0-10)
    
        In terms of how visible the player is and how visible the upcoming obstacles are
        
        A score of 0 means that almost nothing is visible in the level and playing the it's layout significantly reduces it's difficuly
        
        A score of 10 means that everything from the player to all the upcoming obstacles are visible
        
        Most levels in this DB should have a relatively high score for this since I prefer to rate the good levels
        
    If the level has repetitive and/or annoying parts and how much they effect the level
        
        Some levels might have a really repetitive gameplay but might have great decoration that got them an epic rating, since this DB also has gameplay in focus this is to filter those out
        
        A score of 0 means that the gameplay of the level is the same and never changes in the entire level
        
        A score of 10 means that there are no parts that get boring or annoying
        
    Whether a level is fun to play or not (keeping the difficulty of the level in mind) (0-10)
    
        Even though some levels are technically not repetitive their gameplay might not be really fun this or they might have repetitive parts that are actually fun, this should be as subjective as possible
        
        A score of 0 means that the level is not fun to play at all (keeping the difficulty in mind)
        
        A score of 10 means that the gameplay is perfect for difficulty and is really fun
        
        If another factor is significantly effecting the gameplay then it should be rated accordingly
            
            For example if the visibility of the level is ruining the gameplay it should be rated with the effects of visibility since players will be playing with the bad visibility
    
            For example if the gameplay is a bit bland the great sync with the music is making it really fun to play it should be rated with the effects of the great music sync
           
        Most levels in this DB should have a similar score for this to the repetitivenss and annpying parts, not always however.
