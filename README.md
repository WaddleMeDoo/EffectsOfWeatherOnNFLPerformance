# EffectsOfWeatherOnNFLPerformance

In both popular and pundit discussion of NFL matches, a commonly recurring storyline is the effect of weather (or in the case of indoor or closed dome games, the lack thereof) on team performances, in general and for specific franchises.

For instance, it is taken for granted among the NFL community that indoor games may result in more efficient passing compared to those held in cold weather. Wind is also a variable that many fans believe to be a factor in offensive performances, to the point where fantasy football enthusiasts will throw footballs in the parking lot in an attempt to predict game script. Of course, precipitation is generally understood to be a factor too, as teams may stick to the ground game in heavy rain or snow.

The effect of weather is also often mentioned for specific franchises. For instance, the modern Miami Dolphins stereotypically underperforms when forced to play away from tropical Hard Rock Stadium. On the flip side, away teams in Miami are allegedly impacted by the scorching heat on the visitor sideline in early fall.

Goal: The goal of this project is to determine whether factors of weather create significant differences in NFL offensive performances. If such a difference exists, the goal is to also quantify the extent to which each franchise is affected by these variables.

Method:
We will analyze the effect of the following weather conditions on NFL play:
- Indoor (True/False)
  - For the purposes of this analysis, stadiums with a retractable dome would be counted as indoors if the dome is closed and outdoors if the dome is open
- Wind Speed
- Wind Gust
- Temperature
- Temperature delta from home stadium
  - This will be the difference between the on-field gameday temperature and either the monthly temperature average for the team’s home city OR 70℉ for teams home-based in indoor stadiums OR the higher of the two for teams home-based in retractable dome stadiums

The following metrics will be used to measure team performance:
- Win Percentage
  - How do different weather conditions affect the probability that a team will win?
- Passing EPA
  - How do different weather conditions affect the effectiveness of a team’s passing attack?
- Rushing EPA
  - How do different weather conditions affect the effectiveness of a team’s rushing attack?
- Passing-to-rushing-play ratio
  - How do different weather conditions affect a team’s propensity to pass?
