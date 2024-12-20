[Back to Portfolio](./)

Battleship
===============

-   **Class:** CSCI 235: Procedural Programming
-   **Grade:** A
-   **Language(s):** C++
-   **Source Code Repository:** [Battleship](https://github.com/ThunderboltG/Battleship)  
    (Please [email me](mailto:jpingalls@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

Battleship was the final project of CSCI 235.

Computer code was provided by the instructure, Dr. Hayes.

## How to compile and run the program

How to compile and run the project.

```bash
g++ -Wextra -std=c++17 -o battleship Battleship.cpp
./battleship
```

## UI Design

The game is run through the CLI. The first screen is the ship randomizer. This allows the user to randomize the position of their ships before the game begins (See Fig 1). Once the user confirms their ship placement, the game begins with the user getting the first move (see Fig 2). The user and the computer will take turns shooting at different positions on the board. After each round of action, the board will display the results of both the user and the computer's turns, display the current board state, and prompt the user for their next move (see Fig 3). The game checks the validity of each move, notifiyng the user of either an invalid move or an already made move (see Fig 4 and Fig 5). Whenever the computer or the user sinks a ship, a notification appears telling what ship has been sunk (see Fig 6). Once either the computer or the user sinks all enemy ships, the board will go to the results screen. This screen reveals the ships of both boards, and states the winner of the game (see Fig 7). The program then exits, allowing the user to rerun the start command to play another game.

![screenshot](battleship/battle_shipselect.png)  
Fig 1. The launch screen and ship select menu

![screenshot](battleship/battle_startingboard.png)  
Fig 2. The starting board of the game

![screenshot](battleship/battle_default.png)  
Fig 3. Feedback when an invalid move occurs

![screenshot](battleship/battle_invalid.png)  
Fig 4. Feedback when an invalid move occurs

![screenshot](battleship/battle_alreadyshot.png)  
Fig 5. Feedback when an already shot area occurs

![screenshot](battleship/battle_sunk.png)  
Fig 6. Feedback when a ship is sunk

![screenshot](battleship/battle_win.png)  
Fig 7. Game finished screen

## 3. Additional Considerations

While the program is currently not suited for a two-player match, a small change to main could allow for two players to face each other. The board would most likely be invisible to both players while the game is ongoing.

For more details see [Battleship](https://github.com/ThunderboltG/Battleship).

[Back to Portfolio](./)