# RuneShape

### A daily puzzle game where you must correctly identify a RuneScape item from its shape.

#### Available at https://runeshape.today

- **Frontend**: React (in TypeScript)
- **Backend**: Django Rest Framework (in Python)
- **Database**: PostgreSQL
- Hosted on **AWS EC2** (frontend + backend) and **AWS RDS** (database)

#### Game overview:

- Both a RuneScape 3 and Oldschool RuneScape puzzle are available.
- Each puzzle resets at 00:00 UTC each day.
- You have a maximum of 5 guesses to correctly identify the in-game icon.
- After each incorrect guess, as a hint, you will be told the difference between the release date of the item you guessed, and the mystery item.
- Once the game ends, you can view the global stats (eg see second image below) for today's puzzle, and can copy your result to your clipboard in order to share with friends.

### Game Images:

#### Game in progress (left) & game completed (right):
![image1](https://github.com/finahdinner/RuneShape/assets/87808600/5f5d7626-2569-474d-9a30-e934a828bd61)

#### Global stats:
![image2](https://github.com/finahdinner/RuneShape/assets/87808600/ef8f5b22-478a-4198-a62b-2850d0b0cf93)
