14.01.2025
- Yesterday, I made the item generator and the different items: bad guys (for now triangles) and good guys (for now circles). There is a 1 in 3 random chance that a generated item will be a triangle and 2 in 3 chance that it'll be a circle. Today, I worked some more on that. I also added a start screen and play button, a Game Over screen, and a win game screen. I worked on the game over and game won conditions and I fixed some issues that I had with the collision. 

15.01.2025
- Today I fixed a bug with the random generator. Basically, it would sometimes generate triangles that have the properties of "GoodGuys", so I searched through my whole code to find out why that happens, until I finally realized that it does that because my code calls the randomize function twice - once for the name of the sprite and once for the image source of it. So I just made a seperate variable that stores both of these outcomes of the random function, and that fixed the problem. I also added acceleration for the spawning of items, now each item spawns 0.95 faster than the last item. And lastly, I started working on the art, and I drew a beautiful egg: both a normal and cracked version of it.

16.01.2025
- I drew the rest of the items of the game, and I looked through a real recipe for chocolate cake to draw my objects based on. Now, the game has: cats, pianos, froggy chairs, flour, milk, sugar, eggs, chocolate, and butter. Then I animated the ingredients to change into their "cracked" version once they hit the ground. I also cleaned up some of the code.

17.01.2025
- I worked some more on the art of the game and changed the object sizes. Now, the non-edible objects are twice as big as the ingredients. I also fixed a slight bug there was with the score points of the game and I made a global variable for proportionalObjectSize, so that the objects are proportional to the size of the screen. I also thought about the design that I'll use for the win screen, game over screen, the main character, etc.

20.01.2025
- I drew hearts for the game and implemented them so that they would change depending on the number of lives that you have (how many objects you can still miss). I also added points to the screen of the game which show you how many more points you have to get until you win. I then, cleaned up some of the code and added some comments where I thought were necessary. 

21.01.2025
- I added a restart button and fixed some of the issues that came along with it. I also worked on some bugs that appeared in my code and also renamed some of my variables to make the whole code more easy to follow.

22.01.2025
- I worked some more on the code. I changed the CSS code so as to center it and to make it not take up the whole screen. I also drew the animations for the hearts beating, and changed the heart code to be a class so that I can animate it easier. I also animated the main character, who is now a pink-haired girl holding a bucket, and I animated a cake spinning, which will be on the Game Won screen.

23.01.2025
- I added the spinning cake to the game, but due to technicalities, I decided to leave it as a "Special Item", which basically gives you more lives. I then drew the start screen, game won screen (which, coincidentally, also has a cake), the instruction screen, and the game over screen. I fixed some minor bugs that occured within the game and cleaned up the code. I tested if everything worked properly. I also chose a color palette and basically changed the colors of the game a bit. I added a background the point counter. Lastly, I changed the title of the project and added a favicon, which I drew.

