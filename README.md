# Quiz 1
### 1. Which Unity window contains a list of all the game objects currently in your scene?
### Svar: Hierarchy

### 2. True or False: Visual Studio is not a part of Unity. You could use a different code editor to edit your C# scripts if you wanted to.
### Svar: True
 
### 3. What best describes the difference between the below images, where the car is in the second image is further along the road?
### Svar: The second car’s Z location value is higher than the first car’s

### 4. In what order do you put the words when you are declaring a new variable?
### Svar: [access modifier] [data type] [variable name] [variable value]

### 5. Which of the following variables would be visible in the Inspector?
### Svar: speed

### 6. What is a possible value for the horizontalInput variable?
### Svar: 0.52

### 7. What is true about the following two lines of code?
### Svar: They will both move an object at the same speed

### 8. Which of the following lines of code is using standard Unity naming conventions?
### Svar: Line D 

### 9. Which comment would best describe the code below?
### Svar: // Rotates around the Y axis based on left/right arrow keys

### 10. The image below shows the preferences window that allows you to change which script editing tool (or IDE) you want to use. Where would you click to choose an alternative code editing tool?
### Svar: The red box (External Script Editor)

# Quiz 2

### 1. If it says, “Hello there!” in the console, what was the code used to create that message?
### Svar: Debug.Log("Hello there!");

### 2. If you want to destroy an object when its health reaches 0, what code would be best in the blank below?
### Svar: health < 1 

### 3. The code below creates an error that says, “error CS1503: Argument 1: cannot convert from 'UnityEngine.GameObject[]' to 'UnityEngine.Object'”. What could you do to remove the errors?
### Svar: Either A or D

### 4. Which comment best describes the following code?
### Svar: // If player collides with another object, destroy the object

### 5. If you want to move the character up continuously as the player presses the up arrow, what code would be best in the two blanks below:
### Svar: GetKey(KeyCode.UpArrow) 

### 6. Read the documentation from the Unity Scripting API and the code below. Which of the following are possible values for the randomFloat and randomInt variables? 
### Svar: randomFloat = 100.0f; randomInt = 0;

### 7. You are trying to randomly spawn objects from an array. However, when your game is running, you see in the console that there was an “error at Assets/Scripts/SpawnManager.cs:5. IndexOutOfRangeException: Index was outside the bounds of the array.” Which line of code should you edit in order to resolve this problem and still retain the random object functionality?
### Svar: Line 4

### 8. If you have made changes to a prefab in the scene and you want to apply those changes to all prefabs, what should you click?
### Svar: The “Overrides” drop-down at the top of the Inspector


### 9. Read the documentation from the Unity Scripting API below. Which of the following is a correct use of the InvokeRepeating method?
### Svar: InvokeRepeating(“Spawn”, 0.5f, 1.0f);
 

### 10. You’re trying to create some logic that will tell the user to speed up if they’re going too slow or to slow down if they’re going too fast. How should you arrange the lines of code below to accomplish that?
### Svar: 7, 8, 3, 4, 6, 1, 2, 5, 9

# Quiz 3

### 1. You are trying to STOP spawning enemies when the player has died and have created the two scripts below to do that. However, there is an error on the underlined code, “isAlive” in the EnemySpawner script. What is causing that error?
### Svar: The “bool” in the PlayerController class needs a “public” access modifier

### 2. Match the following animation methods with its set of parameters
### Svar: 1B, 2A, 3C

### 3. Given the animation controller / state machine below, which code will make the character transition from the “Idle” state to the “Walk” state.
### Svar: setFloat(“Speed_f”, 0.3f);

### 4. Which of these is the correct way to get a reference to an AudioSource component on a GameObject?
### Svar: Line A

### 5. When you run a project with the code below, you get the following error: “NullReferenceException: Object reference not set to an instance of an object.” What is most likely the problem?
### Svar: There is no object named “Player” in the scene

### 6. Which of the following conditions properly tests that the game is NOT over and the player IS on the ground
### Svar: Line C

### 7. By default, what will be the first state used by this Animation Controller? 
### Svar: “NotCrouched”

### 8. Which of the following variable declarations observes Unity’s standard naming conventions (especially as it relates to capitalization)?
### Svar: 1 and 5

### 9. Which of the following is most likely the condition for the transition between “Run” and “Walk” shown below?
### Svar: Speed_f is Less than 0.5


### 10. Which of the following do you think makes the most sense for a simple movement state machine? 
### Svar: Image A
