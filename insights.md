# Key Insights – Titanic EDA

1. **Gender was the strongest factor.** Women survived at 74.2% versus 18.9% for men.
   Even within each class, women had much higher survival rates (96.8% in 1st class vs 50.0% in 3rd).
2. **Passenger class mattered.** Survival dropped from 63.0% (1st) to 47.3% (2nd) to 24.2% (3rd).
   Third-class men fared worst, with only 13.5% surviving.
3. **Children and family travellers had better odds.** Children (12 and under) survived at 58.0%,
   and passengers travelling with family survived at 50.6% versus 30.4% for solo travellers.
4. **Fare is positively correlated with survival (+0.26)**, reflecting its link to class.

## Conclusion
Survival was shaped by gender, class and family situation. "Women and children first"
is visible in the data, but class created a large gap even among women. Missing ages
(about 20% of rows) were imputed with the median by sex and class, so age-based findings
are approximate.
