

Features 

1. **Hand Tracking:**
   - Utilizes the `mediapipe` library for hand tracking.
   - The position of the player's hand, specifically the index finger tip, controls the paddle's position on the screen.

2. **Game Elements:**
   - Displays a virtual air hockey table on the screen.
   - Implements a puck that moves around the screen with an initial velocity.
   - Paddle is controlled by the player's hand.
   - Generate multiple target positions randomly on the screen.The target image has been provided.

3. **Game Logic:**
   - The puck bounces off the walls of the screen.
   - If the puck collides with the paddle, its vertical velocity reverses.
   - If the puck enters the region of a target, the player scores a point, and the target disappears.
   - After hitting a target,  puck's velocity is increased to make the game more challenging.

4. **Score and Timer:**
   - Displays the player's score on the screen.
   - Implements a timer indicating the remaining time to play.

5. **Game Over Conditions:**
   - The game ends when either all targets are hit or the time limit is reached.
   - Displays a game over message with the player's final score.

6. **User Interface:**
   - Provide clear and visible text displaying the player's score and the remaining time.

7. **User Interaction:**
   - Allows the player to quit the game by pressing the 'q' key.

8. **Visual Effects:**
   - Visual effects to represent the puck, paddle, and targets on the screen.

9. **Congratulations Message:**
   - If the player hits all the targets within the time limit, a congratulations message is displayed.



