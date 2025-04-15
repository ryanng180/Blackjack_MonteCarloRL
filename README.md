<h1>CNY Blackjack with Monte Carlo Reinforcement Learning</h1>
<h2>SDSC4026 Sys modelling and Simulation</h2>

For my exchange program at CITYUHK, I wanted to try my hand at creating a General Golf Course Simulation Tool to Keep Delays Down and Throughput Up. But my groupmates thought it was too complex, it was fair becuase they were new to coding projects and I was also very much unsure of the math behind this really intriguing project. Will be adding this to my list of crazy project ideas.

Redefining the blackjack problem: I realised that Blackjack would be very popular topic among my batchmates and hence we settled on a Chinese New Year's (CNY) Blackjack, a refreshing take from the usual casino styled Blackjack. Blackjack was the perfect topic for us because it gave us the freedom to abstract the problem as we liked; the different contexts for blackjack games allowed for different levels of game abstraction. Essentially, we could dictate the level of difficuly whenever we liked. I could ensure that the coding workload for my teammates was not too steep such that I am able to help with debugging if required. More importantly, I could challenge myself as I saw fit. We initially decided to implement just Monte Carlo First Visit but I had the time and bandwidth to attempt 3 others. Overall, Reinterpreting the game of Blackjack by contextualising it to the CNY version at home really gave us the most freedom to explore the gamut of strategies across various levels of modelling and simulation techniques.

<h2>Methodology</h2>
We model five player profiles after common Chinese New Year (CNY) Blackjack archetypes, along with a sixth profile powered by Monte Carlo Reinforcement Learning (MCRL), serving as a theoretical benchmark 
for optimal decision-making. To evaluate the effectiveness of various Blackjack strategies under our custom Chinese New Year house rules, we simulate 300 rounds for each player profile in Python. Players are 
categorized into two groups: decision-focused (Profiles 1,2,3,5,6) and bet-sizing strategies (Profiles 4,5).

![image](https://github.com/user-attachments/assets/d1596f21-6fc2-48dd-8a0c-ceef052bfb13)
![image](https://github.com/user-attachments/assets/e192e050-293e-4d5f-9cd7-39e915c10d90)

Having done Monte Carlo Simulation on a basic stock portfolio, it was the perfect time for me to try my hand at Monte Carlo Reinforcement Learning for the Blackjack Project.
Under the moniker of Player Profile 6, I explored 4 Monte Carlo Reinforcement Methods: 
<ol>1. Monte Carlo First Visit</ol>
<ol>2. Monte Carlo Every Visit</ol>
<ol>3. Monte Carlo On Policy</ol>
<ol>4. Monte Carlo Off Policy</ol>
![image](https://github.com/user-attachments/assets/604b81c8-dfb5-4bda-a5a8-751367a7f640)

<h2>Resources</h2

<h2>Challenges</h2>

<h2>Reflections</h2>

<h2>Improvements</h2>
Try Temporal Difference Learning, or a hybrid model 
