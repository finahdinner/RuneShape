# RuneShape

### A daily puzzle game where you must correctly identify a RuneScape item from its shape.

#### Available at https://runeshape.today

- **Frontend**: React (in TypeScript)
- **Backend**: Django Rest Framework (in Python)
- **Database**: PostgreSQL

#### Game overview:

- Both a RuneScape 3 and Oldschool RuneScape puzzle are available.
- Each puzzle resets at 00:00 UTC each day.
- You have a maximum of 5 guesses to correctly identify the in-game icon.
- After each incorrect guess, as a hint, you will be told the difference between the release date of the item you guessed, and the mystery item.
- Once the game ends, you can view the global stats (see second image below) for today's puzzle, and can copy your result to your clipboard in order to share with friends.

### Game Images:

#### Game in progress (left) & game completed (right):
<img width="1697" height="1263" alt="runeshape_before_after" src="https://github.com/user-attachments/assets/98598418-c266-46c6-b9a9-f7e41a8f6274" />

#### Global & User-specific stats:
<img width="1243" height="1287" alt="runeshape_stats" src="https://github.com/user-attachments/assets/1b76fd0c-1b5a-4120-9365-36d412df0f07" />
