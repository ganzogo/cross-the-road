# Cross The Road

These steps are available at [bit.ly/cross-the-road-steps](https://bit.ly/cross-the-road-steps).

## Step 1: Remix the Starter Pack

Follow the link: [bit.ly/cross-the-road-starter](https://bit.ly/cross-the-road).

Next tap **Remix**. When the project loads, give it a new name. Have a look around the project.

* *What sprites do you have available?*
* *What costumes do the sprites have?*
* *What sounds are available?*
* *What backgrounds do you have?*
* *Is there any code already?*

---

## Step 2: Position the player at the bottom of the screen

When the game starts, we want to position the player at the bottom of the screen, in the middle. Add this code to the player sprite.

![Step 2 - player sprite](img/step-02-01.png)

* *Can you position the player at the top of the screen instead?*

---

## Step 3: Make the player walk to the right

Add a forever loop and inside check to see if the right arrow is being pressed. If it is, move the player to the right. 

![Step 3 - player sprite](img/step-03-01.png)

* *Can you make the player move faster or slower?*

---

## Step 4: Make the player walk in the other directions

Now the player can walk right. Next let’s make them walk left, up and down. 

* *When the player moves left, can you make them look to the left?*

---

## Step 5: Add a car

Instead of using the car sprite directly, we will clone it. That will let us have more than one car on the screen at the same time.

To do that, hide the sprite, then clone it and then when the clone is created, position it and show it. We’re going to put it on the left of the screen. Add this code to the car sprite.

![Step 5 - car sprite](img/step-05-01.png)

* *Can you pick a different car image?*
* *Can you pick a random car image?*

---

## Step 6: Make the car move

Next we will make the car move from left to right across the screen. We will use repeat until for this. Once it gets across the screen, we can hide the clone.

![Step 6 - car sprite](img/step-06-01.png)

* *Can you make the car move faster or slower?*
* *Can you make the car move at a random speed?*
* *Can you make the car move in a different lane of the road?*
* *Can you make the car move in a random lane of the road?* **TRICKY** 🤔
* *Can you make the car move from right to left?*

---

## Step 7: Add more cars

Instead of just creating one clone, add a forever loop and create a clone every 2 seconds.

![Step 7 - car sprite](img/step-07-01.png)

* *Can you create clones more often or less often?*

---

## Step 8: Make the car squash the player

Right now, the cars will just keep driving even if the player is in the way. When the car touches the player, broadcast the message “game over”.

![Step 8 - car sprite](img/step-08-01.png)

And in the player sprite, when you receive the message, switch the costume and stop the game.

![Step 8 - player sprite](img/step-08-02.png)

* *When you start the game again, how do you unsquash the player?*
* *Can you play a sound when the player gets hit?*
* *Can you display the game over sprite when the player gets hit?*
* *Can you make the player not get hit in each of these two situations?* **TRICKY** 🤔

![Step 8 - Hit area 1](img/step-08-03.png)
![Step 8 - Hit area 2](img/step-08-04.png)

---

## Step 9: Add some coins

Go to the coin sprite and add this code to create 10 clones at random positions.

![Step 9 - coin sprite](img/step-09-01.png)

* *Can you create more than 10 coins?*

---

## Step 10: Let the player collect the coins

![Step 10 - coin sprite](img/step-10-01.png)

* *Can you play a sound when the player collects a coin?*
* *Can you add a variable to count how many coins you have collected?*

---

## Step 11: Finish the game when the player reaches the top of the screen

Add this code to the forever loop in the player sprite.

![Step 11 - player sprite](img/step-11-01.png)

And add this inside the you-win sprite.

![Step 11 - you-win sprite](img/step-11-02.png)

* *Can you play a sound when the player wins?*
* *Can you make it so you only win if you have collected all the coins?*

---

## Challenges

* *Can you draw more sprites and use them in your game?*
* *Can you add more levels?*
* *Can you give the player more than one life?*
* *Can you add a screen to choose your character?*
* *Can you use the train sprite? How can you draw a train track?*
* *Can you use the log sprite?*
