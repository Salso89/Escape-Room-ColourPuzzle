# Escape-Room-ColourPuzzle
Complete escape room puzzle code

Puzzle-Server/ Puzzle-GUI-Client:

This program is designed for a Raspberry Pi-based puzzle game. It includes various imports, such as GPIO control for hardware, LED control, socket communication, and a custom "hubclient" module for managing actions and device registration.

The code defines a device with various actions ("Start Game" and "Reset Game"), registers the device with a hub, and sets up a socket server for communication with a client. The main game logic involves lighting up LEDs in a specific pattern (color sequence), which the player must replicate by pressing buttons on a GUI touchscreen. If the player successfully replicates the sequence, it unlocks a "lock" controlled by a GPIO pin, allowing the game to be reset or quit.

The program also includes threading for handling LED animations and socket communication, along with functions to control the LEDs, restart the game, and handle user inputs. The game can be restarted and played again, or it can be exited by selecting options based on user input.

Overall, this code creates an interactive puzzle game with LED sequences and physical button input, controlled by a Raspberry Pi and interacting with a central hub for managing devices and actions.

VR World:

This HTML code displays an interactive 3D environment using the A-Frame framework, featuring text, 360-degree images, and interactive elements that respond to user input, providing an immersive experience within a web browser. The user will view three objects that will allow them to realise the colours red/green/blue are equal to one/two/three, therefore giving them the key to the colour sequence allowing them to input the correct input into the physical GUI touchscreen








