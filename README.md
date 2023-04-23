Download Link: https://assignmentchef.com/product/solved-301115-advanced-statistical-methods-worksheet-1
<br>






<h1>Probability</h1>

<ol>

 <li>Given the events <em>A </em>and <em>B </em>and their probability <em>P</em>(<em>A</em>) = 0<em>.</em>2, <em>P</em>(<em>B</em>) = 0<em>.</em>4 and <em>P</em>(<em>A ∩ B</em>) = 0<em>.</em>1, for each of the following compound events, draw the probability diagram and shade the region of interest and compute probability of the compound event.

  <ul>

   <li><em>P</em>(<em>A<sup>C</sup></em>)</li>

   <li><em>P</em>(<em>A ∪ B</em>)</li>

   <li><em>P</em>(<em>A ∪ B<sup>C</sup></em>)</li>

   <li><em>P</em>((<em>A ∩ B</em>)<em><sup>C</sup></em>)</li>

   <li><em>P</em>(<em>A<sup>C </sup>∪ B<sup>C</sup></em>)</li>

   <li><em>P</em>(<em>A<sup>C </sup>∩ B<sup>C</sup></em>)</li>

   <li><em>P</em>((<em>A<sup>C </sup>∩ B<sup>C</sup></em>)<em><sup>C</sup></em>)</li>

   <li><em>P</em>((<em>A<sup>C </sup>∪ B<sup>C</sup></em>)<em><sup>C</sup></em>)</li>

  </ul></li>

 <li>A <em><sub>Magic the Gathering </sub></em>deck of cards contains 60 cards; 20 of the cards are land cards and the remaining 40 cards are non-land cards. If I draw seven cards from the deck at random, what is the probability that I get:

  <ul>

   <li>three land cards?</li>

   <li>more than three land cards?</li>

   <li>between two and four land cards?</li>

  </ul></li>

</ol>

What is the expected number of land cards when I draw seven cards at random (use Wikipedia to help with this)?

<ol start="3">

 <li>You and a friend play a game where you shuffle a deck of 52 playing cards, then reveal the top card. If the card is of the suit “hearts”, then you win $2. If the top card is not of the suit “hearts”, then you give your friend $1 and you must play again.

  <ul>

   <li>What is probability that you reveal a “heart” after the first shuffle?</li>

   <li>What is the probability that you don’t lose money?</li>

   <li>What is the expected number of games that you must play and the expected winnings (use Wikipedia again)? 4. The birthday problem is a famous problem in probability, in which we calculate how many people we would need to gather in a room before there is at least a <sub>0<em>.</em>5 </sub>probability that at least two of these people share a birthday. We assume that birthdays are uniformly distributed across the year, and that all birthdaysare independent (i.e. no twins). Use <sub>R </sub>to calculate the probability for a room with <em><sub>n </sub></em>people and plot the probabilities for various values of <em><sub>n</sub></em>. Use a reference line to show <em><sub>p </sub></em><sub>= 0<em>.</em>5 </sub>on your plot. Choose sensible limits for the <em><sub>x </sub></em>and <em><sub>y </sub></em></li>

  </ul></li>

</ol>

<h1>Conditional Probability</h1>

<ol>

 <li>Given the events <em>A </em>and <em>B </em>and their probability <em>P</em>(<em>A</em>) = 0<em>.</em>2, <em>P</em>(<em>B</em>) = 0<em>.</em>4 and <em>P</em>(<em>A ∩ B</em>) = 0<em>.</em>1, for each of the following events, draw the probability diagram and shade the region of interest and compute probability of the events.

  <ul>

   <li><em>P</em>(<em>A|B</em>)</li>

   <li><em>P</em>(<em>B|A</em>)</li>

  </ul></li>

</ol>

1

Are events <em><sub>A </sub></em>and <em><sub>B </sub></em>independent?

<ol start="2">

 <li>The probability of living in the outback, given that you have seen a UFO is 0.4. The probability of living in the outback, given that you have not seen a UFO is 0.2. Given that the probability of seeing a UFO is 0.01, what is the probability of seeing a UFO, given that you live in the outback?</li>

</ol>

<h1>Random Variables</h1>

Given the following random variables, use Wikipedia to find the expected value and variance. Make sure to describe what the expected value means for each distribution.

<ul>

 <li><em><sub>X </sub></em>is Binomial, with number of trials <em><sub>n </sub></em><sub>= 12 </sub>and probability of success <em><sub>p </sub></em><sub>= 0<em>.</em>2</sub></li>

 <li><em><sub>Y </sub></em>is Hypergeometric with number of trials <em><sub>n </sub></em><sub>= 10</sub>, number of success states <em><sub>x </sub></em><sub>= 25 </sub>and number of failure states</li>

</ul>

<em>y </em>= 45.

<ul>

 <li><em><sub>Z </sub></em>is Geometric with probability of success <em><sub>p </sub></em><sub>= 0<em>.</em>1</sub>.</li>

 <li><em><sub>A </sub></em>is Normal, with mean <em><sub>µ </sub></em><sub>= 10 </sub>and standard deviation <em><sub>σ </sub></em><sub>= 5</sub>.</li>

 <li><em><sub>B </sub></em>is Poisson with rate <em><sub>λ </sub></em><sub>= 4<em>.</em>5</sub>.</li>

</ul>

<h1>Bayes’ Theorem</h1>

Consider the following scenario. You have a disease that is present in 1% of the human population. You have a test for the disease that is 95% accurate, meaning that 95% of the time a person with the disease will receive a positive test result, and 5% of the time they will receive a negative test result. Conversely, a person without the disease will receive a positive test result 5% of the time, and a negative test result 95% of the time. Translate the above problem formulation into probability statements

(i.e. use <em><sub>D </sub></em>for the event that the individual has the disease and <em><sub>D</sub><sup>C </sup></em>for the event that they do not, <em><sub>T </sub></em>for a positive test, <em><sub>T</sub><sup>C </sup></em>for a negative test). Use Bayes rule to calculate the probability that a person with a positive test result has the disease (hint: you will need to apply the law of total probability to obtain <em><sub>P</sub></em><sub>(<em>T</em>)</sub>). Does the result surprise you? Use <sub>R </sub>to plot the accuracy of the

test against the probability that a person with a positive test result has the disease for accuracies of between 0% and 100%.

2