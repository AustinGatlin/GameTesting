# Game Critique 1 
## Details
* Title: Sheepwith
* Developer: Robert Docks 
* Release Date: June, 2017

## Summary
  Sheepwith is a game that gives you one simple task, use a plane to rescue lost sheep and bring them back to their pen. Your character is an airplane equipped with a rope and a grabber at the end of it. The gameplay consists of navigating through various maps finding, and rescuing the sheep scattereed throughout it. In the beginning, the game is as simple as that. However, here are thirty five missions in total, with each one being harder than the last. Those missions are devided into five distinct regions, with each region providing a new and unique obsticle for you to overcome, such as wolves which leap towards and kill the sheep, a dimly lit cave, and more. 

  The gameplay mechanics are relatively simple, you fly forwards to keep yourself in the air, and you position yourself so your grabber touches the sheep to pick them up. If you touch any part of the environment you die and respawn at whatever sheep pen you most recently delievered a sheep to, and continue on. To deliver the sheep you've picked up back to a sheep pen, you have the option of either flying low enough so that the sheep touch the pen and they're automaticallyl deposited in it, or you can let go of them and hope that you let go at the right angle and velocity to have them land in the pen. 
  
## Overall Impressions
Despite it's simplicity, my impression of Sheepwith was extremely positive. The overall art and sound design was reminiscent of 90's DOS titles and quickly bread a sense of familiarity. The controls were made and felt natural, and the levels provided enough of a challenge to keep you constantly engaged which made for a great gameplay experience. 

## Things to Test

As a tester, four functions that I would immediately begin to test are: 

1. Plane controls, particularly changing directions from left to right and from right to left. When the player changes left or right, the controls allow you to smoothly transition from one direction to the other by keeping it consistent; pressing forward still moves your plane in the directio it's facing, left still makes it face more upwards, and right more downwards. If I were a tester this would be one of the first things I tested to make sure that the face up and face down controls didn't change with the switching of directions. 

2. The next feature I would test is the rope and grabber. The rope and grabber simply dangle from the bottom of the airplane, with no way of controlling them aside from how you move the airplane. As a tester, my main concern with the robe and grabber would be in how it interacts with other objects. Does it pass through the airplane or collide with it? Is it supposed to? Can the grabber get caught on the terrain or obsticles, impeding movement? 

3. Another feature I would be sure to test is how the sheep behave and interact with the world, in particular, their pens. While some of the sheep stay completely still, others will jump back and forth in a small area. What I would want to test is whether or not the sheep that jump would be able to jump into their pen on their own. If they could, it could potentially lead to game breaking results. 

4. The othe major functionality that I would test would be the game's time system. Time, in this game, only effects what you can see on your screen. This can most clearly be seen if you die while an object is falling, then, when the object is once again on screen, it resumes its fall from exactly where it was when you died. While this feature itself may seem like a bug on the surface, it's a tool that the developer uses for triggering certain events. For example, often times in a level there will be wolves positioned near sheep, but will only lunge for the sheep once they are both on screen. This gives you time to grab the sheep before it can be eaten. If the game's timing does not work and those events progress without being on screen, then certain levels would be impossible to complete

