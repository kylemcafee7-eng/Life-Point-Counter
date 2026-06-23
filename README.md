# Life-Point-Counter
A multiplayer Life Point Counter built in C# WinForms with tools like dice rolls, coin flips, prepared actions, and automatic victory detection. It tracks wins, losses, and deck data through a stats file, offering a fast, organized way to manage competitive matches.



The Life Point Counter is a multiform C# WinForms application designed to manage competitive matches by tracking player life point totals (primarily for the card game Yu-Gi-Oh), recording outcomes, and providing gameplay utilities commonly used in card and tabletop games. Once the match starts, the application loads the main interface, which displays each player in a structured layout where they can enter their name, the name of their deck, current life points, and dedicated controls for adding or subtracting preset or custom values (8000 by default). The system uses a Player class and a List<Player> to maintain clean state management, ensuring each player’s data is updated consistently across the interface.

The main form includes several utility tools to support gameplay flow, such as a coin flip, a six sided die, a twenty sided die, and a prepared action feature that allows players to queue a life point change or the victory condition before applying it. 

A separate statistics form reads and parses a text file, presenting aggregated data such as total wins, losses, and usage trends. This gives players insight into performance over time and adds analytical depth to the application. 
