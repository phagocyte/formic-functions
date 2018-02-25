# Formic Functions - Ant Queen of the Hill contest

This is the code behind the JavaScript programming contest hosted on Programming Puzzles & Code Golf Stack Exchange.

## [View/enter the contest here.](https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest)

![dance floor ant GIF](https://i.stack.imgur.com/7xiOD.gif)

<sup>Not actual game footage.</sup>

Each player starts with one ant - a queen, who collects food. Each piece of food can be held or used to produce a worker. Workers also collect food to be brought back to the queen.

All players compete in one arena. The winner is the queen holding the most food after she has taken 30,000 turns. The catch is that the ants can only communicate by changing the colors of the arena squares, which may also be changed by rival ants...

## Leaderboard

After 7,685 games (over 11 days), there are still some joint places. These results are based on the players as they were at 20:56 UTC Wednesday 14th February 2018. After months in first place, Windmill has finally been brought down to third place by updates to Vampire which take advantage of the rail structure, although new defences put in place mean it hasn't dropped far. New entry Lightspeed is vying for first place with Glider, but a new tournament is currently running with further player updates, so a new leaderboard will be posted in about a week...

<table><thead><tr><th>Position<th>Player<th>Score<th>Games<th>Score per game</thead><tbody><tr><td>1<sup>st</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136158#136158" target="_blank">Glider - Draco18s</a><td>63206<td>4621<td>13.68<tr><td>1<sup>st</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/153688#153688" target="_blank">Lightspeed - Alion</a><td>62527<td>4574<td>13.67<tr><td>3<sup>rd</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/143980#143980" target="_blank">Windmill - GNiklasch</a><td>58681<td>4539<td>12.93<tr><td>4<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136694#136694" target="_blank">Miners on a Rail - dzaima</a><td>52730<td>4575<td>11.53<tr><td>4<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/138434#138434" target="_blank">Single Queen - Crispy</a><td>52203<td>4537<td>11.51<tr><td>4<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135188#135188" target="_blank">Lone Wolf - Dave</a><td>52386<td>4627<td>11.32<tr><td>7<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135108#135108" target="_blank">Forensic Ants - Dave</a><td>41726<td>4507<td>9.26<tr><td>8<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/142207#142207" target="_blank">La Reine Bleue - Some runner guy</a><td>39963<td>4619<td>8.65<tr><td>9<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135818#135818" target="_blank">Claustrophobic Queen - DLosc</a><td>38652<td>4541<td>8.51<tr><td>9<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135272#135272" target="_blank">HalfThere - Christopher</a><td>37685<td>4460<td>8.45<tr><td>9<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135278#135278" target="_blank">Straighter - ppperry</a><td>37971<td>4521<td>8.40<tr><td>9<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135984#135984" target="_blank">Vampire Mk.5 (Quixotic) - Dave</a><td>37148<td>4490<td>8.27<tr><td>13<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135790#135790" target="_blank">Pierce - fireflame241</a><td>34759<td>4452<td>7.81<tr><td>13<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/145980#145980" target="_blank">Hoppemaur - Pelle Lundkvist</a><td>35309<td>4538<td>7.78<tr><td>15<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135183#135183" target="_blank">Wildfire Mk.3 - Dave</a><td>29024<td>4593<td>6.32<tr><td>15<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135359#135359" target="_blank">Ziggurat v3.0 - Zgarb</a><td>27473<td>4576<td>6.00<tr><td>17<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135104#135104" target="_blank">Romanesco Road - trichoplax</a><td>26002<td>4554<td>5.71<tr><td>18<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135156#135156" target="_blank">Antdom Walking Artist - Frenzy Li</a><td>22881<td>4581<td>4.99<tr><td>19<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135157#135157" target="_blank">Black Hole - Draco18s</a><td>20730<td>4565<td>4.54<tr><td>19<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/140551#140551" target="_blank">FireFlyMkII - Moogie</a><td>20326<td>4591<td>4.43<tr><td>19<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135107#135107" target="_blank">Roman Ants Mk.2 - Dave</a><td>19896<td>4585<td>4.34<tr><td>19<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/139964#139964" target="_blank">Monorail - QuoteBeta</a><td>19047<td>4527<td>4.21<tr><td>23<sup>rd</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135103#135103" target="_blank">Brownian Jig - trichoplax</a><td>15547<td>4641<td>3.35<tr><td>24<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/136022#136022" target="_blank">Explorer - ATaco</a><td>14206<td>4565<td>3.11<tr><td>25<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135271#135271" target="_blank">Medusa - PhiNotPi</a><td>11260<td>4522<td>2.49<tr><td>26<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/153601#153601" target="_blank">Langton's ant - Alion</a><td>8830<td>4547<td>1.94<tr><td>27<sup>th</sup><td><a href="https://codegolf.stackexchange.com/questions/135102/formic-functions-ant-queen-of-the-hill-contest/135125#135125" target="_blank">Trail-eraser - ppperry</a><td>5114<td>4512<td>1.13</tbody></table>

Each game involves a randomly selected 16 players. At the end of each game, a player's score is the number of players whose queen holds less food than theirs. The average score per game is used to determine the leaderboard order. Joint places indicate that the order of players is not yet consistent between 6 subsets of the games played so far. The list of games is split into 6 subsets because this is the minimum number that will give a probability of less than 5% that a given pair of players will be assigned distinct places in the wrong order.
