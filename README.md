# 3DGame
JHU game class.

Repetition
DESIGN DOCUMENT
By Xin Tan and Kerry Wang


Introduction	1
Game Summary Pitch	1
Inspiration	1
Player Experience	2
Platform	2
Development Software	2
Genre	2
Target Audience	2
Concept	3
Gameplay overview	3
Theme Interpretation	3
Art	5
Design	5
Audio	6
Music	6
Sound Effects	6
Game Experience	6
UI	6
Controls	6
Development Timeline	7

Introduction
Game Summary Pitch
Repetition is a roguelike deck-building game where the main character traverses through various domains (levels) of the game to unlock new character stories and obtain buffs. 
Inspiration
Slay the Spire
Slay the Spire let user to attempts to ascent a spire created through procedural generation. It is 2D and the user gains new cards as rewards from combat and other ways. It is famous for balancing the difficulty of the game against the randomness of the roguelike.This the key inspiration for combat of this game.

Arknights
It is a Tower Defense roguelike game. You will use different characters to defend the enemy. It uses Hope to get different characters, and stronger characters would cost more hope. This game is famous for its art style and variety of its game. I think one thing it is good for this game is to limit the length the player can see. It has an Anti-interference index. When you have more anti-interference indexes, you can see more nodes in the map. Also you can use the anti-interference as a key to open a new node.

Minecraft
Minecraft is the main inspiration for the artistic style and design of the game. Considering the high requirement for intricate art styles running on different platforms, Minecraft’s simple yet elegant art style would be a good approach for our game. Additionally, the in-game music provides a calming and immersive experience for players, which is another aspect worth implementing. 
(Interesting mod https://vaulthunters.gg/)
Player Experience
In a tower filled with a level on each floor, players will attempt to beat each level and make decisions that require planning and management. The player must learn to navigate around chance and attempt to beat each level with the shortest time possible.

Platform
The game is developed to be released on windows PC
Development Software
JMK for programming
Genre
Roguelike, SandBox

Target Audience
With randomness at hand and generally low passing criterion, this game provides an engaging experience for casual players and also those who enjoy some good lore. However, if the player wishes to get the best loot and complete levels in the shortest time, a lot of strategizing is at work, providing a challenge for veteran and meta players to achieve higher heights. Hence, this game is targeted to both casual and competitive players.


Concept
Gameplay overview
The player controls their character along with others and various buffs/cards to move across the levels. By navigating through each level, the player must strategically manipulate the paths and buffs they choose to pass each level and not require a restart from the very beginning.

Like traditional roguelike games, our game will include nodes such as Unknown, Merchant, Treasure, Rest, Enemy, and Elite. Players will experience gaining rewards or fighting in procedurally generated world nodes. Players will enhance their strength through these encounters and attempt more battles. We plan to offer around 15 different combat scenarios (with approximately five different environments). Players can move freely within the scenes, and random treasures will also appear within them. There will be around 5 elite battles and 2 final battles, corresponding to different endings.

Theme Interpretation 

‘Repetition’ interpretation - For roguelike games, it is a repetition. Also for this game players fall in a repetition of a certain period in our world setting. 
Players need to choose different choices in Unknown nodes to explore more about the world and go to the second ending. Players may repeat this game multiple times as usual in a roguelike game, and each time they would unlock more cards based on what they do in the game. Also they can repeat to try higher levels of difficulty.
Art
Design
We wanted to make the game style look more uniform, so we chose two styles, low-poly and voxel. The main reason for this is that these two styles have more free modeling assets and we can reduce the impact of the art on the overall gameplay. For example, a single environment may look like this. We would build around 10-15 small rooms similar to this.


*It is picture from some package on online asset store*


Audio
Music
To add immersion to the game, we will add music to match the gameplay (ex. Combat music, selection screen music, etc). Inspirations could be pulled from Cytus, Genshin Impact, and other instrumental music. (Examples to be included)
Sound Effects
To add more flare and polish to the experience, a multitude of environmental sound effects will give weight and feedback to the player’s actions. Rather than foley, or otherwise realistic sounds, synthesized blips, bloops, and whooshes are used.

Game Experience
UI
We will use a similar style for our user interface. There will click a button to change settings. A map. A place to see what buff(weapon) you got.
Controls
Keyboard
	Arrow keys / WASD






Development Timeline(Not finalized Version)

MINIMUM VIABLE PRODUCT
Sep 25 - Part 2: 3D scenes and user interaction (Ch 2, 3)
Layout the hand designed environment with basic polygons
Implement player movement
Implement game loop for finishing/restarting
Finish the games basic narrative design
Oct 16 - Part 3: Polygon meshes (including characters) and materials (Ch 4, 5)
Add meshes and more details to environment
Implement the auto generated mechanism of the path
Imp lement cards of combat
Dec 2 - Part 4: Physics, special effects, terrains, and sound (Ch 6-9)
Implement trade, buff, ending
Add music and sound effects in different scenario
Implement the “key” and hidden room algorithm.


