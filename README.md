## Title: Missing Professor Detective Game

**Description**: This is a MERN stack-based web application designed to improve users' soft skills, such as problem-solving, critical thinking, and communication. The game revolves around the mysterious disappearance of a prominent professor. Players must employ their detective skills to solve a series of clues and puzzles, unveiling the truth behind the missing professor.

**Technologies used**:
- MongoDB: for data storage and retrieval
- Express: for server-side routing and middleware
- React: for building the user interface
- Node.js: for running JavaScript on the server-side
- MUI: for responsive design

**Features**:
- User authentication: users can securely sign up, log in, and log out.
- Game mechanics: players navigate through a series of clues and puzzles to uncover the mystery surrounding the missing professor.
- Leaderboard: users can track their progress and compare their scores with other players.
- Admin dashboard: administrators have access to manage user accounts, game settings, and view game analytics.

**Soft Skills Assessment**:
To assess the soft skills mentioned, specific methods are used for each clue within the game:

1.	Problem Solving: Players encounter challenging puzzles, and their approach, analytical thinking, and logical reasoning abilities are observed.
2.	Memory and Recall: Complex images are presented, and later, players are tested on their ability to remember and accurately recall specific details from the image.
3.	Visual Spatial Reasoning: Players engage with visual representations that require understanding and manipulation of spatial relationships.
4.	Critical Thinking: Players analyze complex scenarios or situations, evaluating information objectively, considering different perspectives, and making reasoned judgments.
5.	Analytical Thinking: Players decipher clues, make connections, and apply analytical thinking to deduce the correct solution.

By utilizing these methods, the game assesses players' soft skills, providing valuable insights into their abilities and behaviors.

**Flow Chart of the game**":

            +-------------------+
            |   Pregame Page    |
            +---------+---------+
                      |
                      |
                      v
            +-------------------+
     +------|      Clue 1       |
     |      +---------+---------+
     |                |
     |                |
     |                v
     |       +-------------------+
     +-------|     Solve Puzzle   |
             +---------+---------+
                       |
                       |
                       v
             +-------------------+
      +------|      Clue 2       |
      |      +---------+---------+
      |                |
      |                |
      |                v
      |        +-------------------+
      +--------|  Confusing Image  |
               +---------+---------+
                         |
                         |
         +---------------+---------------+
         |                               |
         |          Correct Answer       |
         |                               |
         v                               v
 part 2 
 
 
 +-------------------+           +-------------------+
|      Clue 3       |           |     Dead End 1    |
+-------------------+           +-------------------+
         |                               |
         |                               |
         v                               |
+-------------------+                     |
| Descriptive Image |                     |
+-------------------+                     |
         |                               |
         |                               |
         v                               |
+-------------------+                     |
|      Clue 4       |                     |
+-------------------+                     |
         |                               |
         |                               |
         v                               |
+-------------------+                     |
|  Combination Lock |                     |
+-------------------+                     |
         |                               |
         |                               |
         v                               |
+-------------------+                     |
|      Clue 5       |                     |
+-------------------+                     |
         |                               |
         |                               |
         v                               |
+-------------------+           +-------------------+
|   Laptop Lock     |           |     Dead End 2    |
+-------------------+           +-------------------+
         |                               |
         |                               |
         v                               v
+-------------------+           +-------------------+
|    Game Complete  |           |    Game Over      |
+-------------------+           +-------------------+


**Installation**:
1. Clone this repository to your local machine.
2. Install Node.js and MongoDB on your machine.
3. Run `npm install` to install dependencies.
4. Start the server with `npm start` in backend folder.
5. Start the client with `npm start`.
