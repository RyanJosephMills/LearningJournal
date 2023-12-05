# LearningJournal

# 3/10/2023

Problem
When starting this semester, I was immediately struck with a learning problem as this was the first time I had used Unity starting from scratch in year 1. We mainly had been given a project that had gotten most of the simple parts out of the way and didn’t require us to do anything, and when I was at college for the two years of my course, I never used Unity as my course would only ever use Unreal engine.

Solution
The only way I could solve this problem was to go onto YouTube and the official Unity website. I had to learn the essential tools to start a Unity project, for example, coding the basic coding of the character's movement and the  ability to make the player jump and finally add gravity to the player.

# 10/10/2023

Problem
A problem I have encountered in making my first bit of code for my character's movement is that the screen mouse will not mount to the centre of the screen and is completely visible. I have had a look around at some people's code online; however, I have not been able to solve the problem, so one way I will try and solve this problem is by asking around in class and see if people in the class can point me in the correct direction.

# 13/10/2023

I had yet to gain experience making videos using OBS on my laptop, so I had to follow tutorials online to get more experience making videos on OBS.

# 17/10/2023

Problem
I am still developing a decent idea in the 3D style of game that I can do within the time limit. This is because I have very little knowledge of Unity, so I am finding 3D game designs much harder.

Solution
I am going to counter this instead of going into a 3D design. I will go into the 2D design and make a game like that, as it will be much easier and simpler to think about

# 31/10/2023

I learnt how to code a character to move left to right using A and D inside Unity using the 2D game design.

# 31/10/2023

I learnt how to code the player so that when you click on the W key, the player will jump up.

# 03/11/2023

I learned how to make an opening and closing mechanic inside Unity for my game.

# 05/11/2023

I used a tutorial to create a death barrier inside the game so that if the player misses the platform, the game will restart from the beginning.

# 07/11/2023
I followed a tutorial that allows the player to take damage from an enemy character. That is placed inside of the world. 

# 09/11/2023

I am having a problem with my code so that when an enemy is inside the game, and I jump over him, the key will not open the door; however, when the enemy isn't inside the game, the door works perfectly fine.

# 14/11/2023

I was having a problem with my door opening and closing. 

What was happening was I would jump over the enemy, pick up the key, and try and open the door; it wouldn't move, and what I didn't realise was that because I had two collisions on my player, it was registering as if the key was picking up the key twice so it was opening and closing the door at the same time.
So, I had to add some code to the key behaviour script to make it pick up the key only once.

# 21/11/2023

Using some tutorials online, I created a title screen for my game with a working play button and a button that could take you to the options menu and then back to the main menu screen.

# 25/11/2023

I tried to create a pause menu; however, when I did, none of my buttons worked as intended.

# 27/11/2023
I created a Moving platform using the enemy movement code, which works similarly.

# 28/11/2023

I have a problem with my platform code.

My problem with it is when my character makes contact with the platform, it gets stuck to the platform, and my character will now move with the platform. I can only get away if I restart the game. I need to look at the code and see what is wrong.

# 01/12/2023

I have figured out what is wrong with my Platform Code.

The problem with the code was I had two different types of code. The first bit of code was on collision, which means that it was the objects as a whole instead of the box collision, so I needed to change it to an on-trigger enter 2D, and that is the reason why it wouldn't break away as the other bit of code was an on trigger exit. It needs to make contact with the thing that this code was assigned to.

# 05/12/2023

I learned how to create a Pause Menu with working buttons to resume the game, return to the main menu, and finally quit the game.

# 05/12/2023

I had a problem with the Pause menu that I made.

What would happen is when I pause the game, everything freezes; however, the game music would continue playing.

All I needed to do was go inside the pause menu code and refer to the music source I wanted to Freeze. Then, inside the Key buttons, you must put music.play under resume and music.Pause under Pause
