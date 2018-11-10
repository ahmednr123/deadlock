# Deadlock Recovery - Computer Graphics Project

## Setting up

  - Install required libraries:
	- `sudo apt-get update`
	- `sudo apt-get install libglu1-mesa-dev freeglut3-dev mesa-common-dev`
	
  - Compile the program:
  	- `g++ main.cpp -o main -lglut -lGLU -lGL`
    
  - Run application:
  	- `./main`
    
## Navigation

  - Click on an **"Example"** to execute.
  
  - Press ***Space*** to proceed with each step 
  	- *( **FINDING A CIRCLE** -> **BANKER's ALGORITHM** -> **PROCESS TERMINATION** )*
	
  - Press ***Esc*** to get back to the navigation screen.

## Screenshots

### Navigation Screen
![Navigation Screen](screenshots/main_1.png)

### Finding a cycle
![Finding a cycle](screenshots/main_5.png)

### Safe State (No cycle found)
![Safe State (No cycle found)](screenshots/main_3.png)

### Cycle found
![Cycle found](screenshots/main_6.png)

### Bankers Algorithm
![Bankers Algorithm](screenshots/main_22.png)

### Process termination
![Process termination](screenshots/main_8.png)

### System Recovered
![System Recovered](screenshots/main_9.png)


> The code was written in 3 days, so cut me some slack!
