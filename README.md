# Assessment-HarvadX-Combinations-and-Permutations-UsingR
## EDX Assessment for HarvardX Data Science: Probability course.

# The exercises were made using R language using a notebook in RStudio
## You will find the resolution of each exercise (containing code + explanation) on the PDF uploaded to this Repo. 
### You can find this exercises in HarvardX course (EDX) called "Data Science: Probability", this is one of many assessments at the Course. 

## EXERCISES:
1. Two teams, say the Celtics and the Cavs, are playing a seven game series. The Cavs have a 60% chance of winning each game. What is the probability that the Celtics win at least one game? Remember that the Celtics must win one of the first four games, or the series will be over!
  **Instructions:**
    - Calculate the probability that the Cavs will win the first four games of the series.
    - Calculate the probability that the Celtics win at least one game in the first four games of the series.
      
--> Use p_cavs_win4 as the probability that the Cavs will win the first four games of the series.

2. Create a Monte Carlo simulation to confirm your answer to the previous problem by estimating how frequently the Celtics win at least 1 of 4 games. Use B ← 10000 simulations. The provided sample code simulates a single series of four random games, simulated_games.
  **Instructions:**
- Use the replicate function for B ← 10000 simulations of a four game series. The results of replicate should be stored in a variable named celtic_wins.
- Use the set.seed function to make sure your answer matches the expected result after random sampling;
- Create an object called celtic_wins that replicates two steps for B iterations: (1) generating a random four-game series named simulated_games, then (2) determining whether the simulated series contains at least one win for the Celtics. 
  
3. Say you’ve drawn 5 balls from a box that has 3 cyan balls, 5 magenta balls, and 7 yellow balls, with replacement, and all have been yellow. What is the probability that the next one is yellow?
  **Instructions:**
    - Assign the variable p_yellow as the probability of choosing a yellow ball on the first draw.
    - Using the variable p_yellow, calculate the probability of choosing a yellow ball on the sixth draw.


4. If you roll a 6-sided die once, what is the probability of not seeing a 6? If you roll a 6-sided die six times, what is the probability of not seeing a 6 on any of those rolls?
  **Instructions:**
    - Assign the variable p_no6 as the probability of not seeing a 6 on a single roll.
    - Then, calculate the probability of not seeing a 6 on six rolls using p_no6. Do not assign it to a variable.
