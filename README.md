# AB-Test-for-Online-Gaming-Company
Using R to conduct an A/B test to thoroughly assess the sales team's proposal’s impact

**Case objective:**
To examinate whether the proposal of
decreasing rank tolerance parameter to 4 points and increasing the
cut-off parameter to 20 seconds could improve the revenue.

**Background information:**
The company creates revenue by in-game virtual
item purchase and ad clicks. The longer time the play is, the more
likely the virtual items would be purchased. The longer time the idle
time is, the more ad are likely to be clicked. Players with closer rank
could longer the playing time. Playing with bot only spends short time.
On average, each ad click could result in \$0.01 income and in-game
virtual item purchase values between \$1 to \$5. The original matching
algorithm is that the rank tolerance is 5 points and cut-off time is 15
second. The new proposed one is that the rank tolerance is 4 points and
cut-off time is 20 seconds. Supposedly, renuvue from both ad clicks and
in-game virtual item purchase would be increased.

**Key stakeholder concerns:**
As the new proposal is under test, if the
revenue is decreasing rather than increasing as expected, the potential
loss would be huge. Also, longer idle time could undermine the user
experience, which brings potential customer loss risk.

Decision point: After A/B test, if the revenue could be proved to show
significant increase, the new proposal could be adopted, or the original
one would be kept.

**A/B Test Design** 
Hypotheses: H0: The new proposal has no significant
effect on revenue (revenue regarding new proposal \<= revenue regarding
original algorithm). H1: The new proposal increases revenue (revenue
regarding new proposal \> revenue regarding original algorithm).

HO: The new proposal has no significant effect on more ads clicked
during idle time (\<=) H1: (\>)

H0: The new proposal has no significant effect on increase of game
duration. (\<=) H1: (\>)

H0: The new proposal has no significant effect on increase of in-game
purchases. (\<=). H1: (\>)
