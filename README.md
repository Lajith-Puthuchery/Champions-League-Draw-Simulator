# Champions-League-Draw-Simulator
Simulating RO16 Draw using Python

Inspiration: The most recent RO16 draw had to be redone due to an error with the computer based algorithm governing the draw which led me to this mini-project.

The draw had the following restrictions:

1. Teams from the same country/association cannot draw each other
2. Group Winners can draw only 2nd place finishers
3. A team cannot face a team from the same group

Teams.csv : A csv file containing the details of the teams qualified for the draw.

Initially a ball was picked of any 1st placed team, then a ball was picked of a team that was included in the 'Possible Opponnents' column of that team. Draws were done using the random library in python.

check_implies function checks if there is any team that can play only 1 team at the given time

Reference: https://medium.com/swlh/simulating-uefa-champions-league-draw-with-python-5709244a9224
