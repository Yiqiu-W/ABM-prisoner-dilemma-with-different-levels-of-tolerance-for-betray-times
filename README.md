#### ABM-prisoner-dilemma-with-different-levels-of-tolerance-for-betray-times

##### stretegy: "act-randomly" "cooperate" "defect" "tit-for-tat" "tit-for-two-tats" "unforgiving" "act-based-on-last-5-times" 
##### "tit-for-tat" = if betrayed last time, defect this time
##### "tit-for-two-tats" = if betrayed for the last two time, defect this time
##### "act-based-on-last-5-times" = must not betray me any time in the last five times, or I defect

##### Situation 1:
##### human is acting based on the last 5 choices of the partner(cooperate as long as the partner did not defect more than once in the last five times) and the computer choose tit-for-tat strategy(it would defect if last time the parter defected)

##### In the first round, because the human remembers that the partner has defected 3 times in the last 5 times and the computer remebers the partner did not defect last time, the human chooses to defect but the computer chooses to cooperate. So the human gets to run free and gains 5 points but the computer gets severly punished gains 0 point the average-score-line of human goes up and that of computer goes down.

##### Then in the second round, because the human remebers that the partner has defected 2 times in the last 5 times and the computer remembers the partner defected last time, both the human and computer choose to defect(confess) So they both get punished and gain 1 point. The average-score-lines of them go down as neither of them gains high points like 3 or 5.

##### In the third round, because the human remebers that the partner has defected 2 times in the last 5 times and the computer remembers the partner defected last time both of them choose to defect. Again, both of them gain only 1 point.

##### In later rounds, they always choose to defect and gain 1 point as a result.
##### Eventually both players get average scores slightly higher than 1.

##### Situation 2:
##### human is still acting based on the last 5 choices of the partner like in situation 1 but the computer start to consider the last two choices the partner made(it would defect only when the partner defected both times in the last 2 rounds).

##### In the first round, the human chooses to defect like in Situation 1 but the computer chooses to cooperate because the partner did not defect in the last two rounds So the human runs free and gains 5 points but the computer gets severly punished gains 0 point. Pretty much like what happened in the first round in Situation 1.

##### In the second round, because the human remebers that the partner has defected 2 times in the last 5 times but the computer remebers the partner only deected once in the last two rounds, human chooses to defect again but the computer chooses to cooperate So human gains 5 points and the conputer gains 0 point again The average-score-line of human continues to go up but that of the computer continues to go down.

##### However, in the third round, because the human remembers the partner only defeceted once in the last 5 times and the computer remebers the partner defected both times in the last 2 times, the human chooses to cooperate but the the computer chooses to defect. So this time, the computer gains 5 points but the human gains 0 point. The average-score-line of human starts to do down but that of the computer starts to go up.

##### In the fourth round, both players choose to cooperate and gain 1 point. The average-score-line of human go down slightly and that of the computer continues to go up

##### Such trends continues in the following rounds. Both of the plays always choose to cooperate. Eventually both players get average scores close to 3 but the average score of human is slightly greater than 3 but that of the computer is slightly lower than 3


##### Discussion:
##### it seems that in both situations, in the first round, the player who act based on last 5 times always "outsmart" the play who choose tit-for-tat/tit-for-two-tats 
##### the act-based-on-last-5-times player betrayed the partner and gain 5 points.

##### when the other player choose tit-for-tat(if you betary me last time, I will betray you), it starts to betray the betrayer in later rounds and the first player always have more than one feeling-betaryed memory in the last five times so it never cooperates. Both of the players want to gain 5 poins for themselves and always betray each other. So they end up with average score very close to 1(both confessing the crime and get medium punishment)

##### when the other player choose tit-for-two-tats(more forgiving, I will betray you only if you have betrayed me for the last two times) the act-based-on-last-5-times player "outsmart" the partner in the first 2 rounds. but the second player "outsmart" the act-based-on-last-5-times player in the third round and get 5 points. then both players always cooperate. So they end up with average score very close to 3(both denying the crime and get minimum punishment if cannot run free)


##### Given that both players remeber that the partner cooperated 2 times in the last two rounds but defected in the previous 3 rounds when the game starts, if one player cannot stand with more than 1 time of betray in the last five times and the other player always copies the last choice of its partner, they eventually lose faith in each other and never cooperate. However, if one player cannot stand with more than 1 time of betray in the last five times while the other player is more tolerative and always cooperate as long as not betrayed in the last 2 times, eventually they believe in each other and always cooperate.

##### Tolerance boosts trust and cooperation and guarantees relatively high gain for both.
