# NBA-Lottery-Rigging-Analysis
A Monte Carlo analysis of NBA Draft Lottery outcomes (1990-2025) to evaluate fairness through 100,000 simulated drafts.

## Is the NBA Lottery Fair?
In 2025, the Dallas Mavericks shocked the NBA world. They traded away 5-time All-Star Luka Dončić—only to win the #1 draft pick (with just a 1.8% chance) and secure top prospect Cooper Flagg. Fans questioned whether this improbable outcome was luck... or something more.

This project uses statistical simulations to explore whether NBA Draft Lottery results align with expected probabilities—or show signs of potential bias.

--- 

## Objective
To test the fairness of the NBA Draft Lottery by comparing real-world results to outcomes generated via Monte Carlo simulations.

## Hypotheses
 - H₀ (Fair): Lottery outcomes reflect random chance based on official odds.
 - H₁ (Unfair): Outcomes deviate from what would be expected under a fair system.

---

## Methodology

### Data Collection
 - Scraped historical draft lottery results from RealGM (1985–2025).
 - Focused analysis on 1990–2025, when the weighted lottery system was introduced.

### Monte Carlo Simulations
 - Ran 100,000 lottery simulations per year based on official odds.
 - Compared actual draft outcomes to simulated distributions.

### Fairness Analysis
 - Calculated deviation of real results from simulated averages.
 - Generated an empirical p-value to test for statistical significance.

--- 

## Results
- **No significant evidence of foul play was found.**
- The draft outcomes from 1990 - 2025 while improbable, yielded a **p-value of 0.1168** — within the range expected under random variation.

## Takeaways
- **Suspicion ≠ Proof:** Unusual outcomes aren’t necessarily rigged.
- **Rare events happen:** Even 1–2% probabilities will occasionally hit over decades.
- **Perception matters:** The NBA thrives on drama — and compelling narratives, whether rigged or not.
