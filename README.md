# Saving Daily MLB and NHL odds

## Having some fun with BeautifulSoup and python

This program will extract and store daily NHL hockey and MLB baseball matchups and corresponding betting odds. 
 
The betting odds we are scraping represent the moneyline for each team. In order to win a bet on the Moneyline, sometimes referred to as 'straight up', the team that was wagered on must simply win the game.
This may seem obvious, however the term "moneyline" exists because you can also bet on a team to lose by x amount of points or less, or win by x amount of points or more. These are called spreads.
A bet on a spread in baseball is referred to as the runline, lets say Toronto Blue Jays -1.5.
Note the "-" minus sign, this implies that the Blue Jays must win by 1.5 or more, and since you cannot score runs in increments of .5, they must win by 2 or more. This is because if you were to subtract 1.5 from the Blue Jays final score and if they would still win only then would the bet be successful - essentially the Blue Jays have to win by 2 or more. 

scraped from pinnacle.com, represented in decimal form, 

The data is then put into a nice little dataframe and subsequently saved as an excel file which denotes the sport and date in the title.
