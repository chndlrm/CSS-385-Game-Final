# Famine Fighters
Final Project for CSS 385 at UW Bothell

## Part 1: Brainstorming 
Initially my group consisted of three people, none of us had any understanding of Unity. We started by sharing some of our favorite video games and trying to find ways to combine different aspects and mechaics of each game into a cohesive experience. 

After looking at demos from previous classes' final projects, we realized our ambitions might be too high and seemingly not achievable in the seven weeks we had. We reevaluated our ideas and decided to work with an asset pack we found on the Unity Asset Store (link below). The asset pack only contained sprites and no code or built animation sets. 

We decided on a 2D platformer that featured three of the four characters from the asset pack, with the fourth reserved as the final boss. The player would be given a choice at the beginning of the game of which character they wanted to play as, each with their own ability. The abilities are: double jump, dash, and gravity shift. We drew inspiration from games like Super Meat Boy and VVVVV. 

Just before we gave our pitch, we came up with the idea to let the player switch between the characters in-game. The inspiration came from Grand Theft Auto 5 where the player is allowed to switch between its three characters each with their own abilities. This decision allowed us more flexibility with level design. 

Below is a link to the game pitch we gave:

https://docs.google.com/presentation/d/1ynlShPdfaP0fzSeQXWTvgKkCMCZHIch1NbkDB1GvGdo/edit?usp=sharing

After our pitch, we had a new member join our team. 


###### Below is a series of builds we presented to the class demonstrating the progress we made throughout the quarter. 

## Part 2: Prototypes
Our first task was determining what prototypes were necessary to create the game we wanted. 

Inital prototypes:
- Double Jump
- Slide Down Wall
- Change of Gravity
- Item to Unlock Door
- Power Ups
- Switchable characters

We added the dash ability and removed the slide-down-wall prototype from the first build. 

Below is the first build that showcased some of the prototypes we initially decided on. 
https://chndlrm.github.io/CSS385-Build1/

## Part 3: Game Demo
### Changes
- Title screen
- Demo level
- Improved animations
- Traps (fire, spikes, etc.)

https://chndlrm.github.io/CSS385-Build2/

## Part 4: Alpha Play Test
### Changes
- Level selection screen
- Four levels + tutorial
- Background music
- Sound Effects
- Enemies
- Timed medal system

https://kylunr.github.io/FamineFighters/
Note: Pressing the demo button on the title screen crashes the WebGL  

### Feedback

## Part 5: Beta Play Test
### Changes
- Updated tutorial to better explain the mechanics of the game
- More enemies
- Fixed minor bugs

https://chndlrm.github.io/CSS-385-Build4/

### Feedback

## Part 6: Final Play Through
### Changes
- Improved collision system
- Credits Scene
- Updated Title Screen
- Fixed minor bugs

https://chndlrm.github.io/CSS-385-Build5/index.html

## Difficulties and Known Problems
GitHub caused us problems as it didn't always merge scenes correctly. Initially we didn't know which files to push and this caused storage issues on GitHub. 

We used a tile map to construct the terrain which had its own specific collider component. We weren't able to fully figure out how to have the character sprite interact with this smoothly. For example, when the player interacts with a wall, the character shakes; and the wall will act as a floor if the player tries to jump next to it. We eventually determined that because we weren't using the character's RigidBody component to move the character, instead opting to use the default transform system. The issue arises because the RigidBody component doesn't know how to interact with the wall. It doesn't know what to do when the character is at a wall and tries to push through, but the object collider doesn't allow this, hence the shaking. In our attempts to use the RigidBody movement tool, we discovered more issues that made the game unplayable. 

## Tools we Used
##### Communication 
- Discord 
- iMessage

##### File Sharing
- GitHub (didn't work the way we wanted it to)
- Unity Collaboration Tool

##### Assets
- Unity Asset Store
- SoundCloud
- freesound.org
- Canva.com

## What I Worked on
- Hero behavior script
- Hero animation and physics
- Title screen and level selection screen
- Level selection script
- Checkpoint system

## Conclusion and Thoughts
As I said above, my team initially commited to a three-person setup. Our Professor let three different students join our team since every other team had four or more members. While we had no problems with this and willingly adjusted, the first two new members either dropped the class or switched to a different team, our final fourth member joined our team after we had established the concept and prototypes. In the beginning, it was somewhat difficult to catch him up since he wanted to implement code that we already had in place. By the end, we were able to come to a happy medium since he ended up working mainly on enemies and their animations.

## Assets Used
Characters, enemies, traps, obstacles, items, and terrain were found on the Unity Asset Store:
- https://assetstore.unity.com/packages/2d/characters/pixel-adventure-1-155360
- https://assetstore.unity.com/packages/2d/characters/pixel-adventure-2-155418

Background music was found on SoundCloud:
- https://soundcloud.com/adhesivewombat/adhesivewombat-8-bit-adventure

Sound effects were found on freesound.org:
- https://freesound.org/people/dersuperanton/sounds/434462/
- https://freesound.org/people/josepharaoh99/sounds/383240/
- https://freesound.org/people/Natty23/sounds/349182/
- https://freesound.org/people/AudioPapkin/sounds/432292/

The title image was created with Canva.com
