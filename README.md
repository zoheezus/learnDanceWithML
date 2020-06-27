# Author
Zohaib Afridi

# Learn Dance w/ Machine Learning
This is my senior capstone project. I will use an opensource pose-estimation library that will determine the accuracy of a user's movement compared to that of a dance instructors movement parameters, which will be preexisting in the application.

The goal of the user will be to get as close to 100% as possible.

## Installation
### Prerequisites
Make sure node, npm, and git are all installed.

1. `git clone https://github.com/zoheezus/learnDanceWithML.git`
2. create a `default.json` file in the config folder (This is your key, so do not share it with anyone else.)
  * include in it the `mongoURI` and a `jwtSecret`
3. `cd` into the cloned project folder and run the below commands in order
  1. npm install
  2. cd client/
  3. npm install
  4. cd ..
  5. npm run dev