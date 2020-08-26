# Schedule-Forecasting-Excel
Excel example of some simple analysis that accomplishes some really cool stuff -
Uses google trends analysis in advance of the NBA schedule release (example shown on 'Screen Cap Sample' tab) to gather 'Interest Ratings' for all 29 visiting teams.
Creates said ratings for both 'Milwaukee' & 'Wisconsin' as a whole.
'Index' tab combines and weights those ratings, along with title odds and a number of pre-season rankings and gambling odds from different sources to try to get a 'wisdom of the crowd' effect.
'Projections' tab takes rankings and factual data about each game, and uses the results from some regression analysis I ran in R about our games in order to assign value based on 5 variables I found to be highly significant (Day of week, Opponent, Month, days b/w home games, and if the opposing team had a player projected to be a top 5 jersey seller for that year). I also included a 'Misc' category to edit up/down games that had unique outlying circumstances (holiday game, daytime start, etc.).
This then gives us a mathematical index which was really useful, as it accomplished a few things:
  -Gave us a great starting point for the game rankings and tiering
  -Helped ID games that were set to be over/underperformers we may not have seen otherwise
  -Gave us an interval type scale from which to judge these games on rather than a simple ordinal scale. This helped us in previous years identify the need for an additional tier    over the top of our previous highest tier due to an extreme outlier we may not have realized otherwise. 
The 'Sorter' tabs were helpful in breaking up the schedule into our half season and flex (1/4 season) packages and keeping them relatively even in terms of prestige and content.
