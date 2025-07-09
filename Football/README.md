Assume we have the following application that models soccer teams, the games they play, and the
players in each team. In the design, we want to capture the following:

• We have a set of teams, each team has an ID (unique identifier), name, main stadium, and to
which city this team belongs.

• Each team has many players, and each player belongs to one team. Each player has a number
(unique identifier), name, DoB, start year, and shirt number that he uses.
• Teams play matches, in each match there is a host team and a guest team. The match takes place
in the stadium of the host team.

• For each match we need to keep track of the following:

1) The date on which the game is played
2) The final result of the match
3) The players participated in the match. For each player, how many goals he scored,
whether or not he took yellow card, and whether or not he took red card.
4) During the match, one player may substitute another player. We want to capture this
substitution and the time at which it took place.

• Each match has exactly three referees. For each referee we have an ID (unique identifier),
name, DoB, years of experience. One referee is the main referee and the other two are
assistant referee. 
