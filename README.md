# DrivingSimulator
Using conditional loops with Java

In this lab, you will implement your understanding of conditional logic using iterative structures to build a driving simulator of a car that a user can control via the keyboard. 

## Features
At a minimum, a user should be able to:
- Start the car
- Select a gear
- Accelerate
- Brake
- Exit

While these options are basic, the logic found here would form the basis for any driving simulation program.

## Goal
Create a driving simulator to start a car, select a gear, accelerate, brake, and exit. Your task is to refine the program and test the simulator to provide a realistic driving experience. The program needs to be interactive and provide constant feedback to the user.

## Requirements
To make these options actually mean anything, you will need to implement the logic behind them. Let’s examine them:

1. **Start the Car**
   - Starting the car as a first option makes sense—you can’t go anywhere without starting up first! 
   - You need something to hold that value or state. Since this is a yes/no situation, you can use a boolean to hold that value.

2. **Select a Gear**
   - If the car is going to move, it has to be in the correct gear. There are three to choose from, but only two of them should allow the car to move: D (drive) and R (reverse).
   - You need a variable to hold that value, and since this is a text value, you can use a String to hold the value.

3. **Accelerate**
   - You need to know your current speed before you can display the accelerated speed, so you need a variable to hold the speed value.
   - The option to accelerate increases the speed, so you would add a set amount to the speed variable every time a user chooses that option. Since this is a number value, you can use an int to store it.

4. **Brake**
   - When you use the brake, the car slows down, so you only need to subtract a set amount from the speed variable to apply the brakes.

5. **Exit**
   - When the user selects this option, the program will display a goodbye message and end.

## Additional Information
You now have almost all the variables you need to be able to make the car function, but you also need a way to talk to your user. 
- You need to declare a Scanner object to allow input from the keyboard.
- You will also need to capture the choice the user makes, and since this will be a menu number, you can use an int to store this value.

