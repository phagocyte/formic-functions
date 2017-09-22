# Formic Functions - Ant Queen of the Hill contest

This is the code behind the JavaScript programming contest hosted on Programming Puzzles & Code Golf Stack Exchange.

## [View/enter the contest here.](https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest)

![dance floor ant GIF](https://i.stack.imgur.com/7xiOD.gif)

<sup>Not actual game footage.</sup>

Each player starts with one ant - a queen, who collects food. Each piece of food can be held or used to produce a worker. Workers also collect food to be brought back to the queen.

All players compete in one arena. The winner is the queen holding the most food after she has taken 30,000 turns. The catch is that the ants can only communicate by changing the colors of the arena squares, which may also be changed by rival ants...

## Leaderboard

After 2,535 games (over 28 days), there are still a few joint places. These results are based on the players as they were at 20:25 UTC Thursday 24th August 2017. I haven't left this running any longer as there seems to be a high variance in the score of the players competing for second place, preventing second place from being resolved without leaving it running for even longer. Since there have been several new players and updates to existing players during that time, a new tournament is currently running with the latest player updates (effective 22nd September 2017).

<table><thead><tr><th>Position<th>Player<th>Score<th>Games<th>Score per game</thead><tbody><tr><td>1<sup>st</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136694#136694" target="_blank">Miners on a Rail - dzaima</a><td>25561<td>1916<td>13.34<tr><td>2<sup>nd</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136158#136158" target="_blank">Glider - Draco18s</a><td>23783<td>1909<td>12.46<tr><td>2<sup>nd</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/138434#138434" target="_blank">Single Queen - Crispy</a><td>23374<td>1912<td>12.22<tr><td>4<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135188#135188" target="_blank">Lone Wolf - Dave</a><td>23368<td>1959<td>11.93<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135108#135108" target="_blank">Forensic Ants - Dave</a><td>18886<td>1916<td>9.86<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135790#135790" target="_blank">Pierce - fireflame241</a><td>18727<td>1977<td>9.47<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135818#135818" target="_blank">Claustrophobic Queen - DLosc</a><td>17195<td>1945<td>8.84<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135272#135272" target="_blank">HalfThere - 2EZ 4RTZ</a><td>17177<td>1956<td>8.78<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135278#135278" target="_blank">Straighter - ppperry</a><td>16620<td>1918<td>8.67<tr><td>5<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135183#135183" target="_blank">Wildfire Mk.2c - Dave</a><td>16054<td>1932<td>8.31<tr><td>11<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135359#135359" target="_blank">Ziggurat v3.0 - Zgarb</a><td>13229<td>1938<td>6.83<tr><td>11<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135157#135157" target="_blank">Black Hole - Draco18s</a><td>12212<td>1903<td>6.42<tr><td>11<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135104#135104" target="_blank">Romanesco Road - trichoplax</a><td>11855<td>1917<td>6.18<tr><td>14<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135156#135156" target="_blank">Antdom Walking Artist - Frenzy Li</a><td>10189<td>1876<td>5.43<tr><td>15<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135107#135107" target="_blank">Roman Ants Mk.2 - Dave</a><td>9195<td>1962<td>4.69<tr><td>15<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135984#135984" target="_blank">Vampire Mk.3 (now even suckier) - Dave</a><td>9199<td>1970<td>4.67<tr><td>17<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135103#135103" target="_blank">Brownian Jig - trichoplax</a><td>7179<td>1938<td>3.70<tr><td>18<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136022#136022" target="_blank">Explorer - ATaco</a><td>5696<td>1950<td>2.92<tr><td>19<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135271#135271" target="_blank">Medusa - PhiNotPi</a><td>4908<td>1927<td>2.55<tr><td>20<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/139964#139964" target="_blank">Monorail - QuoteBeta</a><td>2954<td>1932<td>1.53<tr><td>20<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135125#135125" target="_blank">Trail-eraser - ppperry</a><td>2885<td>1907<td>1.51</tbody></table>

Each game involves a randomly selected 16 players. At the end of each game, a player's score is the number of players whose queen holds less food than theirs. The average score per game is used to determine the leaderboard order. Joint places indicate that the order of players is not yet consistent between 6 subsets of the games played so far. The list of games is split into 6 subsets because this is the minimum number that will give a probability of less than 5% that a given pair of players will be assigned distinct places in the wrong order.
