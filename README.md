# Football Players' Market Value in Relation to Their Stats and Position

## Author:
- **Mujaheed Abdulmalik**

## Background
This project investigates the relationship between soccer players' age and their market valuation. Footballers' values have increased significantly over the past two decades, influenced by factors such as age, goals, assists, and position. Understanding these relationships can aid football clubs in making informed decisions regarding player acquisitions and sales.

## Data Description
The dataset consists of the 500 most expensive footballers in the world as of 2021. Key variables include:

- **Player Positions**: Grouped into forwards, midfielders, defenders, and goalkeepers.
- **Player Age**: Categorized into four groups:
  - Young Players (17-22)
  - Pro Players (23-28)
  - Peak Players (29-32)
  - Veteran Players (33+)
- **Player Value**: Valuation in millions based on the transfermarkt community.
- **Player Stats**: Combined goals and assists.

## Methodology
### Data Analysis
- The primary variables of focus are player value (continuous, dependent) and player age groups (categorical, independent).
- Due to non-normality and heterogeneity of variance, a Kruskal-Wallis test was used instead of ANOVA to assess valuation differences across age groups.
- Eta squared based on the H-statistic was used to measure the effect size between groups.

### Data Visualization
- Violin plots were utilized to visualize the distribution of player values across different age groups.

## Results
- The study found no significant difference in player valuation scores across age groups.
- Mean valuation scores by group:
  - Young Players: 32.67 million
  - Pro Players: 30.4 million
  - Peak Players: 34.25 million
  - Veteran Players: 41.4 million
- The Kruskal-Wallis test indicated a small effect size, suggesting age alone is not a reliable indicator of market value.

## Conclusion
The research aimed to explore the statistical difference in player valuation across age groups. The findings suggest that age is not a significant standalone factor in determining market value. Future research could consider additional factors such as goals per match, clean sheets, and injury records to provide a more comprehensive understanding.

## References
1. Metelski, A., Kornakov, K., Sharda, R., & Chłapowski, J. (2022). How the value of football players influences a team’s chances of victory - a euro 2020 example. Journal of Physical Education and Sport, 22(1), 167-173.
2. Herm, S., Callsen-Bracker, H. M., & Kreis, H. (2014). When the crowd evaluates soccer players’ market values: Accuracy and evaluation attributes of an online community. Management Review, 17(4), 484-492.
3. Dimitropoulos, P. E., Travlos, A. K., & Panagiotopoulos, S. (2018). Migration and Football Player Market Value: Evidence from Greece. International Journal of Sport Finance, 13(2), 119+.
4. Poza. (2020). A Conceptual Model to Measure Football Player’s Market Value. Revista Internacional de Ciencias Del Deporte, 16(59), 24–42.
5. History, F. (n.d.). The History of Football(Soccer). Retrieved from FootballHistory.org.
6. Bhilawa, & Fahriansyah, R. (2022). THE INFLUENCE OF PERFORMANCE, AGE, AND NATIONALITY ON THE MARKET VALUE OF FOOTBALL PLAYERS. Assets (Madiun, Online), 11(1), 1–9.
7. Sanjeet, S. N. (2021). Most Expensive Footballers 2021 [Data set]. Kaggle.
8. R Core Team (2021). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria.
9. Henning, C. (n.d.). AMOD-5210 Workshop 1: Introduction to Basic and Inferential Statistics in R. Trent Blackboard.
10. Soto-Valero, César. (2017). A Gaussian mixture clustering model for characterizing football players using the EA Sports’ FIFA video game system. RICYDE. Revista internacional de ciencias del deporte. 13. 244-259. 10.5232/ricyde2017.04904.

