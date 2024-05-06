# Cookie Cats AB Test Analysis

## 1. Of cats and cookies
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three"-style puzzle game where the player must connect tiles of the same color to clear the board and win the level. As players progress through the levels, they encounter gates that force them to wait or make in-app purchases to progress, serving the dual purpose of driving revenue and providing players with an enforced break.

## 2. The AB-test data
The dataset includes 90,189 players who installed the game during the AB-test. Key variables include `userid`, `version` (gate at level 30 or 40), `sum_gamerounds`, `retention_1`, and `retention_7`.

## 3. The distribution of game rounds
The analysis begins by examining the distribution of game rounds played by players during their first week. This provides insights into player engagement levels and potential gameplay patterns.

## 4. Overall 1-day retention
1-day retention, defined as the percentage of players returning to the game one day after installation, serves as a crucial metric for assessing game engagement and long-term success.

## 5. 1-day retention by AB-group
Comparing 1-day retention between AB-groups reveals insights into the impact of gate placement on early player engagement.

## 6. Should we be confident in the difference?
Bootstrapping analysis is utilized to assess the certainty of observed differences in 1-day retention between AB-groups, providing valuable insights into the reliability of the results.

## 7. Zooming in on the difference
Kernel Density Plot allows for a closer examination of the percentage difference in 1-day retention between AB-groups, aiding in the visualization of uncertainty and potential effects.

## 8. The probability of a difference
Calculation of the probability that the observed difference in 1-day retention is above 0% offers further insights into the significance of the findings.

## 9. 7-day retention by AB-group
Exploring 7-day retention rates provides a broader perspective on player engagement and retention beyond the initial installation phase.

## 10. Bootstrapping the difference again
Repeating the bootstrapping analysis for 7-day retention reaffirms the findings and strengthens the conclusions drawn from the AB-test.

## 11. The conclusion
Based on the comprehensive analysis, it is recommended not to move the gate from level 30 to level 40 to maintain high retention rates and player engagement. Hedonic adaptation theory provides a plausible explanation for the observed trends, highlighting the importance of strategic gate placement in maximizing player enjoyment and long-term retention.

**Should we move the gate from level 30 to level 40?**
Decision: No, retaining the gate at level 30 is advisable based on the analysis findings and insights into player behavior and engagement.

